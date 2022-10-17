# aircall-gs-cti-dialer
Install a small application inside Google Sheets that will enable the following functionalities directly inside the Google Sheets interface:

- Embedded Aircall CTI Dialer
- Click-to-Dial
- Create Dialer Campaigns

This is possible because Aircall has a broad and well-document public REST API! But please keep in mind the following:

- Installation only needs to be performed once — after, the agent can use the application as many times as they want (without needing to install again)
- In the current version, this application needs to be installed per Google Sheet
  - Each agent will need their own Google Sheet to work from (because the Aircall CTI/Dialer in each Google Sheet must belong to the Sheet Owner)
- The application will only recognize numbers that are in the International E.164 phone number format (e.g. +46 for Swedish phone numbers)
