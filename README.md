# IoT Useful Services

## MQTT Server
-------------

####Installation based on docker 

1. Download the configuration file and store it localiy `<your_local_directory>/config/mosquitto.conf`

2. Execute the folling command

    
 docker run -itd --name=mqtt -p 1883:1883 -v /home/panos/playground/mqtt/storage/mosquitto/config:/mosquitto/config eclipse-mosquitto   
     
3. Check that container started correctly `docker ps`

5.Check MQTT logs `docker logs -f mqtt`
