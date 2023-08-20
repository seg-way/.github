## seGateway - (Seriously Secure Streaming) Event Gateway or loveingly Segway

seGateway is a serious, secure, sensible event gateway solution. What does that mean? Glad you asked

* Serious we know event data (logs) is serious business we take care to handle meaning recieve, process, and deliver that data
* Secure is a focus while confidential data is logs is a bad thing its going to happen do our part to ensure safe handling.
* Sensible nothing is perfect we won't let perfect be the enemey of good enough today but we also won't rest on good enough.

## Powered by

* Syslog-NG why, its fast, its flexible, its powerful, and we don't need to build yet another engine
* Python our extensions to Syslog-NG are written in python when syslog-ng itself is not enough.

## What are our projects

* Sources - Gotta start with a source these connect to a source and bring in the data for processing, apply open telemetry ECS schema where we can.
* Router or Log Path - apply enrichment over ecs schema for delivery.
* Destination Startin with Crowdstrike LogsScale but extensible for others. Deliver the data fully prepared for consumption.
* Implementation - Using Terraform and terragrunt provide ready to run implementations for the most common needs
