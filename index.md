# Project: Enterprise Browser Hardening via Group Policy

## Goal
To implement and enforce centralized security and privacy settings for Microsoft Edge, Chrome, and Firefox in a domain environment.

## Key Technologies
- Active Directory
- Group Policy
- ADMX Templates
- AppLocker
- Windows Server

## Process
- Researched and imported latest ADMX templates for target browsers.
- Designed and tested GPOs to disable password saving, enforce Safe Browsing, and restrict extensions.
- Used AppLocker to block unauthorized browsers, ensuring policy compliance.
- Verified policy application using `gpresult` and browser-specific policy viewers (`chrome://policy`).

## Outcome
Created a deployable set of hardened browser configurations, significantly reducing the attack surface from web-borne threats. Gained deep understanding of policy precedence and management.
