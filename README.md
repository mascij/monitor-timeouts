# monitor-timeouts
Simple bash script that uses ping timeouts as a way to determine network disconnects.  It uses google.com as the domain to ping, this can be easily edited in the script.
## Install

To download this bash script and give it the correct permissions:
```
curl -O https://raw.githubusercontent.com/superman-lopez/monitor-timeouts/master/monitor-timeouts.sh && chmod +x monitor-timeouts.sh
```

## Usage

The bash script can be run without parameters as: 
```
./monitor-timeouts.sh
```

This will run the monitor script for 1 minute.  Alternatively the number of minutes for which the script should run can be passed as parameter:
```
./monitor-timeouts.sh 60
```
This will run the monitor script for 60 minutes.

### Compatibility
This script and the installation instructions has been tested on macOS running Bash version 3 and Ubuntu Linux running Bash version 4.  I expect you can run this script and the installation instructions on most systems running Bash, without problems.
