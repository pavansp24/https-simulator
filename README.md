# https-simulator

Vertx based simple https simulator to simulate api response.

Steps:
clone this repo : https://github.com/pavansp24/https-simulator.git

Make sure java is installed in the environment

import the code in IDE and do mvn clean install

Run the SimulartorVerticle with the vm arguments -Dapi=/auth -Djksfile=/home/pavan/Desktop/server.jks -Dpassword=password -Dlow=600 -Dhigh=1000

You can run the simulator by downloading the executable jar https-simulator.jar. Please use run.sh to run the jar.

Before running the run.sh, Please make sure jks file, password are configured as jvm argument

Ex: 
$JAVA_HOME/bin/java -Dapi=/auth -Djksfile=/home/pavan/Desktop/server.jks -Dpassword=password -Dlow=600 -Dhigh=1000 -jar https-simulator.jar

sh run.sh
