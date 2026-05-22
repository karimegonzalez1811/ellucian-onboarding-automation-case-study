# User On-Boarding Mirror Access Automation

This repository documents a professional automation proof of concept developed during my Customer Solutions internship at Ellucian.

The automation was designed to help streamline Salesforce user onboarding by using a mirror-user access model. The workflow connected ServiceNow, Salesforce, and UiPath to reduce manual effort and improve consistency in onboarding ticket processing.

> Note: This repository is a public case study only. Source code, credentials, internal Salesforce configuration details, and proprietary implementation materials are not included.

## Project Overview

The User On-Boarding Mirror Access Automation was created to reduce manual work in Salesforce onboarding requests.

The process focused on onboarding tickets where a new or updated user needed access modeled after an existing Salesforce user. Instead of manually reviewing and updating user profile details, the automation helped retrieve ticket information, access Salesforce records, mirror access details, and update the ServiceNow ticket.

## Problem

The manual onboarding process required repetitive steps across ServiceNow and Salesforce, including:

- Reviewing onboarding tickets
- Checking whether a mirror user was provided
- Looking up the requested user
- Looking up the mirror user
- Reviewing Salesforce profile details
- Updating user access fields
- Managing permission set-related information
- Updating ticket status and comments in ServiceNow

This process was time-consuming, repetitive, and difficult to scale across many tickets.

## My Role

I developed a UiPath proof of concept that connected ServiceNow and Salesforce workflows to support automated onboarding updates.

My responsibilities included:

- Mapping the onboarding workflow
- Designing the automation logic
- Filtering ServiceNow tickets
- Accessing Salesforce records through API-based workflows
- Extracting requested-user and mirror-user information
- Updating Salesforce user profile details
- Creating flowcharts and documentation
- Demonstrating the proof of concept to stakeholders

## Tools & Technologies

- UiPath
- UiPath Orchestrator
- ServiceNow
- Salesforce Platform
- REST APIs
- Salesforce Connected App
- Data Tables
- Excel-based tracking
- Flowcharts
- Process Documentation

## Workflow Summary

The automation followed a structured workflow:

1. Identify newly created onboarding tickets in ServiceNow.
2. Filter tickets based on request type, assignment group, and state.
3. Check whether a mirror user was provided.
4. Extract the requested user and mirror user information.
5. Access Salesforce through API-based workflows.
6. Retrieve the mirror user’s profile and access details.
7. Update the requested user’s Salesforce profile based on the mirror user.
8. Update the ServiceNow ticket state and comments.
9. Document the result for visibility and follow-up.

## Impact

The proof of concept helped demonstrate how automation could significantly reduce manual onboarding work.

Key results:

- Processed 160 onboarding tickets in approximately 5 hours
- Compared with an estimated 23–53 hours manually
- Helped reduce repetitive Salesforce onboarding work
- Improved consistency in user access updates
- Created a more scalable model for handling mirror-access requests

## Why This Project Matters

This project is an example of workflow automation across enterprise systems. It shows how business process analysis, APIs, automation tools, and system documentation can be combined to reduce manual work and improve accuracy.

The project also strengthened my ability to:

- Translate manual workflows into automation logic
- Work across ServiceNow and Salesforce systems
- Use APIs to connect enterprise platforms
- Document technical workflows clearly
- Explain automation logic to technical and non-technical stakeholders

## Confidentiality Note

This was a professional internship project. For confidentiality reasons, this repository does not include:

- Internal code
- Credentials
- API keys
- Private Salesforce configuration details
- Internal ServiceNow records
- User or employee information
- Proprietary implementation materials

This repository is intended to communicate the project approach, tools, workflow, and business impact at a high level.

## Repository Status

This repository is currently a case study. Future updates may include:

- Sanitized workflow diagrams
- Public process documentation
- A simplified mock version of the workflow
- Sample pseudo-code showing the automation logic without exposing internal systems
