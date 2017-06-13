# MyMQTT_Dioty_Connection_JSON_Ethernet
Publish Dust Sensor to Dioty MQTT broker using Arduino Ethernet Shield

This is my work to publish my Dust Sensor reading to MQTT broker (Dioty)

Hardware used :
1) Arduino UNO clone
2) Original Arduino Ethernet Shield

Library used :
1) PubSubClient : https://github.com/knolleary/pubsubclient

As far as the MQTT broker is concerned, initially, i used HiveMQ MQTT public broker, but since it always up and down, i decided to change to another MQTT public broker, ie Dioty. You just need to register an account there (http://www.dioty.co) and follow my example for topic creation.
