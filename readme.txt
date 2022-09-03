Pre-requsit:
mosquitto 
1. sudo apt-add-repository ppa:mosquitto-dev/mosquitto-ppa
2. sudo apt-get update
3. sudo service mosquitto start #test
4. sudo apt-get install mosquitto
5. sudo apt-get install mosquitto-clients

7. mosquitto -v
1662190009: mosquitto version 2.0.15 starting
1662190009: Using default config.
1662190009: Starting in local only mode. Connections will only be possible from clients running on this machine.
1662190009: Create a configuration file which defines a listener to allow remote access.
1662190009: For more details see https://mosquitto.org/documentation/authentication-methods/
1662190009: Opening ipv4 listen socket on port 1883.
1662190009: Error: Address already in use
1662190009: Opening ipv6 listen socket on port 1883.
1662190009: Error: Address already in use


cargo build

cd /target/debug
$./sub
$./pub


mkae sure 
 sudo apt install openssh-server
 sudo systemctl start ssh
if below gives you error on ssh
