# okta-jamf-offboarding-tool

## Before you get started / prerequisites

Before you get started, you will need:

Access to an Okta tenant with Okta Workflows enabled for your org

Jamf Pro 

## Problem

With companies changing to a more remote friendly environment, its become increasingly difficult to lock down data once an employees termination date is reached. Manual proceess leads to a higher probably of making a mistake. When we were in an office as example, the machine would likely be recovered at the end of the day or when the termination happens. 

## Solution

Build a workflow that locks a machine at the time of deactivation.

1. User gets deactivated
2. Jamf searches for assigned user devices
3. Lock command(s) sent
4. Device renamted to IT Recovery 


![Jamf](https://user-images.githubusercontent.com/87619174/147170464-69341dce-5b7d-482d-bc7d-fe3fcc30d76f.png)

## Resources

https://developer.jamf.com/jamf-pro/reference/classic-api
https://help.okta.com/wf/en-us/Content/Topics/Workflows/connector-reference/jamf/jamf.htm
