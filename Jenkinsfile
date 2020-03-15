#!/bin/bash

mvn clean install
 
docker build -t paymentbilling -f Dockerfile .
docker login -u "hemantakumarpati" -p "Master@1927" docker.io
docker tag paymentbilling hemantakumarpati/paymentbilling:latest
docker push hemantakumarpati/paymentbilling:latest
