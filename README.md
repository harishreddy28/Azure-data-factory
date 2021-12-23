# Azure-data-factory

Lab 1 – Create Azure resources

created an Azure resource group

created data lake storage

created an instance Azure Data Factory

created and authorised a connection from the factory to your data lake storage


Lab2 -Build a Copy data pipeline

-Created a SQL server database to act as exteranl data source

-Created and authorised a connection from the factory to that database

-Created a pipeline to copy data from the database [sales].salesheader table and into data lake

-Ran the pipeline in the debug mode and after publising it to the data facory

Lab 3 – Run SSIS packages in ADF

-created an SSIS Integration Runtime to enable ADF to run SSIS packages

-deployed an SSIS project to the SSIS-IR’s Integration Services catalog

-used the Execute SSIS package activity to run a package in the deployed project

-stopped the integration runtime.

Lab 4 – Build a Mapping Data Flow

-created a mapping data flow

-used Data flow debug to import file schemas (using Import projection)

-created a pipeline to execute your data

-used Data flow debug to run the pipeline from the ADF UX

Lab 5 – Create a reusable pipeline

-created reusable datasets to represent database tables and data lake files generically

-created a generic pipeline using generic datasets

-used the generic pipeline to extract ten different tables with a single pipeline containing only 
three activities.


