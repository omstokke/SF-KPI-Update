# SF-KPI-Update

This repo contains an Apex class for
 - posting query to SSB
 - parsing the resulting JSON
 - checking the current value of a price level adjustment field, and
 - updating the field value

Table of Contents:
- CalloutAndUpdateKPI.apxc - Main Apex class
- GetKPIQuery.txt - Mock response to HttpCallout used for testing
- KPIquery.json - The query posted to SSBs open API
- TestCalloutAndUpdateKPI.apxc - Test Apex class for code coverage
