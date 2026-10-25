# Student Attendance Tracker using n8n

## Project Overview
This project automates student attendance monitoring and sends email alerts to parents when a student is marked absent.

## Technologies Used
- n8n
- Google Sheets
- Gmail
- JSON

## Workflow
1. Schedule Trigger starts the workflow.
2. Google Sheets retrieves student attendance records.
3. IF node checks whether Status is Absent and Alert_Status is Pending.
4. Gmail sends an email alert to the parent.
5. Google Sheets updates Alert_Status to Sent.

## Features
- Automated attendance monitoring
- Email notifications for absent students
- Google Sheets integration
- Automatic alert status updates

## How to Use
1. Import the workflow JSON file into n8n.
2. Connect your own Google Sheets and Gmail accounts.
3. Configure the spreadsheet and workflow fields.
4. Test the workflow using sample attendance data.

## Note
Configure your own account credentials before running the workflow.
