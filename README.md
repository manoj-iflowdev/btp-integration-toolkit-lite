[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/btp-integration-toolkit-lite)](https://api.reuse.software/info/github.com/SAP-samples/btp-integration-toolkit-lite)

# Welcome to ITK Lite 4 Procurement
Welcome to the ITK Lite 4 Procurement BTP application. This application, developed on the Cloud Application Programming Model (CAP), provides a robust alternative to the standard ITK command line utility for transferring master, transactional, and spend data between SAP Ariba systems and back-end ERP environments.

## Requirements
Please see the pre-requisites and the required BTP services in the SAP Discovery Center mission - [Integrate ERP with SAP Ariba Procurement Solution using ITK Lite Application](https://discovery-center.cloud.sap/missiondetail/4260/4518/) before working with this repository.

## Description
With the end of support for the legacy Integration Toolkit (ITK), the ITK Lite powered by BTP allows organizations to integrate non-SAP-ERP systems through an SFTP channel with SAP Ariba cloud solutions. This enables the exchange of master, transactional, and spend data via CSV file upload and download.

Sample View of ITK Lite Admin Application

![Reference Image](/ITKLite.jpg)

## Database Requirement
Use the main GIT branch if you are using PostgreSQL as your database in BTP. If the database is HANA DB, look at the example folder to convert the database HDB and also update MTA.YAML to deploy Multi Target Applications with HANA Database.

## Database Requirement
Use the main GIT branch if you are using PostgreSQL as your database in BTP. If the database is Hana DB , look at the example folder to convert the database HDB and also update MTA.YAML to deploy Multi Target Application with Hana Database.

## Deploy the Application
Prior to running the package and deploy:

Step 1: Go to the app directory and run the "npm i" command.
Step 2: Run the same command "npm i" under the root directory as well.
Step 3: Run the following command to build and deploy the file to the SAP BTP, Cloud Foundry environment.

```
npm run mta:package:deploy
```

## Known Issues
No known issues.

## How to Get Support
If you find a bug or have questions about the implementation, please create an issue in this repository. 

For additional support or professional inquiries regarding this integration toolkit, you may reach out to the maintainer at manoj.gali695@gmail.com or ask a question in the SAP Community.

## Contributing
If you wish to contribute code, or offer fixes and improvements, please send a pull request. Due to legal reasons, contributors will be asked to accept a DCO when they create the first pull request to this project. This happens in an automated fashion during the submission process. This project follows the standard DCO text of the Linux Foundation.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.

## Maintainer
Manoj Gali is a Senior SAP CPI Consultant with over 5 years of experience in SAP integration technologies. Specializing in SAP CPI, PI/PO, and hybrid integration landscapes, Manoj focuses on designing, developing, and optimizing scalable integration solutions to ensure secure, high-performance data exchange across SAP and non-SAP systems.

Key Expertise:
- SAP CPI and PI/PO Integration
- Groovy Scripting and XSLT
- User-Defined Functions (UDFs)
- Hybrid Landscape Optimization

Contact: manoj.gali695@gmail.com