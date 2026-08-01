# **Lab 001 Evidence Log**

## **Evidence Item 1**

Evidence name: Windows System log overview

File name: 01-event-viewer-system-log.png

Source: Windows Event Viewer

Purpose: Shows access to the System log and the general Event Viewer interface.

Observation: The System log contained a large number of Windows-generated events.

## **Evidence Item 2**

Evidence name: DistributedCOM Warning

File name: 02-distributedcom-event-10016.png

Source: Windows System log

Event ID: 10016

Level: Warning

Source: DistributedCOM

Observation: Windows recorded a DistributedCOM warning.

Interpretation: The warning alone did not provide evidence that the system was compromised.

## **Evidence Item 3**

Evidence name: Successful logon

File name: 03-successful-logon-event-4624.png

Source: Windows Security log

Event ID: 4624

Level: Information

Observation: An account was successfully logged on.

Relevant account: SYSTEM and a computer account ending with a dollar sign.

Interpretation: The event was most consistent with expected Windows system activity rather than evidence of an unauthorized human logon.

## **Evidence Handling Note**

The screenshots are being stored as lab evidence. Any personal computer names, usernames, IP addresses, or other identifying information will be reviewed and sanitized before public publication.

