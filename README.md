# sap-ui5
this progect goes throguh all 38 steps in the SAP UI5 Walkthrough here:
https://sapui5.hana.ondemand.com/sdk/#/topic/3da5f4be63264db99f2e5b04c5e853db

I getting started installing the ui cli here:
https://sap.github.io/ui5-tooling/stable/pages/GettingStarted/

# Installation by npm
npm install --global @ui5/cli

# Verify installation
ui5 --help

# Generate package.json
npm init --yes 

# Generate ui5.yaml file
ui5 init

# Define the framework you want to use
ui5 use sapui5@latest

# Add required libraries
ui5 add sap.ui.core sap.m sap.ui.table themelib_sap_fiori_3 # [...]
