# MYY030_Project
Web App In Spring Tools With Microsoft SQL 

A Project Assignment 
Created By George Mitsis

### <div align="center">Setup</div>

---

#### Intellij IDEA Installation Requirements

- Install [**Intellij IDEA**](https://www.jetbrains.com/idea/download/#section=windows) (Community edition is free)
- Import the project as a Maven project, and it runs out of the box

#### Eclipse Installation Requirements

- Install [**Eclipse**](https://www.eclipse.org/downloads/)
- Import the project as a Maven project.

#### Maven

The project uses a Maven wrapper so there is no need to install it to your system as long as you have the JAVA_HOME
environmental variable pointing to your [**Java 8**](https://www.oracle.com/java/technologies/downloads/archive/) installation
folder.

### <div align="center">CONFIGURATION</div>

#### Microsoft SQl Server Tools 2019

- Install From Link [**Microsoft SQl Server Tools 2019**](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16).
- TCP/IP And Server Services Activation [**TCP/IP**](https://blog.devart.com/sql-server-ports.html).

#### Microsoft SQl Server 2022 

- Download From Link [**Microsoft SQl Server 2022**](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) and choose your operation system.
- Read Installation Tutorial [**Tutorial**](https://www.mssqltips.com/sqlservertip/7313/install-sql-server-2022/) in the Database Engine Configuration check mixed mode authentication and give you <b>sa</b> user a password.
- Download and unzip into the installation path the backup files from MYY030_Project/data/*.zip
- Restore the databases DWH, DWH_INTERMEDIATE, DWH_STAGING [**tutorial**](https://www.ibm.com/docs/en/license-metric-tool?topic=database-restoring-ms-sql-server).
