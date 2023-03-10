# Week 0 — Billing and Architecture

## Required Homework/Tasks

### Install and verify AWS CLI works successfully
I installed AWS CLI on my local Windows environment. I documented all the steps in the attached document and ensure that it works.

[Proof of AWS CLI Installation - Document](assets/week0/StepsToInstallAWS_CLI.docx)

![Simple Proof of AWS CLI Installation](assets/week0/Proof_of_AWS_CLI_Installed.png)

### Create Budget

I created a $1 budget to minimise the spend. 

![Proof of Budget creation](assets/week0/Budget.png)

### Create Billing Alarm

I created a billing alarm with all the required parameters set. 

![Proof of Billing Alarm creation](assets/week0/BillingAlarm.png)

### Recreate Conceptual Architecture Diagram

![Proof of Conceptual Architecture Diagram](assets/week0/Cruddur-ConceptualDiagram.png)

[Lucid Charts Shared Link](https://lucid.app/lucidchart/55c19acd-afb7-4776-b5e1-497d20a89ef8/edit?invitationId=inv_5192735b-72e1-4aae-9758-ff3e6e3126d5)

### Recreate Logical Architecture Diagram

![Proof of Logical Architecture Diagram](assets/week0/Cruddur-LogicalDiagram.png)

[Lucid Charts Shared Link](https://lucid.app/lucidchart/cc2bb1c5-6e26-4d1f-a446-469753f3ee1b/edit?view_items=pcFBHJV-hF5V&invitationId=inv_5149cd28-e901-4751-9462-a3971608b6f8)

## Homework Challenges

1. I have included the below components in my Logical Diagram:-
- New Relic - APM tool to gather logs/errors in Frontend and/or Backend
- Cloudwatch - AWS native for monitoring services
- Quicksight - AWS native service for reporting purposes

2. I would like to add Event driven architecture as well.
