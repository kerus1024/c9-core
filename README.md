Cloud9 3.0 SDK for Plugin Development
======================================

Follow these steps to install the SDK:

    git clone https://github.com/kerus1024/c9-core c9sdk
    cd c9sdk
    scripts/install-sdk.sh
    
#### Starting Cloud9 ####

Start the Cloud9 as follows:

    node server.js

The following options can be used:

    --settings       Settings file to use
    --help           Show command line options.
    -t               Start in test mode
    -k               Kill tmux server in test mode
    -b               Start the bridge server - to receive commands from the cli  [default: false]
    -w               Workspace directory
    --port           Port
    --debug          Turn debugging on
    --listen         IP address of the server
    --readonly       Run in read only mode
    --packed         Whether to use the packed version.
    --auth           Basic Auth username:password
    --collab         Whether to enable collab.
    --no-cache       Don't use the cached version of CSS
