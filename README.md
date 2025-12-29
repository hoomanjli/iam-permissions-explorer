# Explorer for IAM Permissions

## Problem Description
In cloud environments, excessive or unused IAM permissions raise security risk and destructive radius. 

Security engineers must be able to recognize dangerous IAM roles, comprehend why they are dangerous, and limit permissions without compromising actual systems.

## Persona of the User
The main user is a cloud security engineer who is in charge of overseeing IAM for several cloud accounts. 
Before making permission changes, they need strong confidence and safety controls because they are restricted by time and risk cautious.

## Design Solution
This design focuses on a simple three-step process:

1. Overview of IAM Risk  
   To assist engineers in rapidly determining where to begin, a prioritized list of IAM roles is arranged by risk.
2. Role Permissions Detail 
   A detailed view that explains why a role is dangerous by displaying which permissions are used versus unused based on the previous 90 days of activity.
3. Guided Remediation
   Recommended low-risk fixes with rollback options and before/after previews to safely reduce permissions.

## Setting priorities Justification:
- Risk-based sorting reduces mental stress.
- Before taking action, usage data creates trust.
- Production interruptions are avoided by safe repair.

## Success Metrics: 
- Reduce in unused IAM permissions
- Time required to detect and address IAM risk 
- Adoption rate of recommended fixes

## Figma Wireframes
Link to Figma design:  
https://www.figma.com/design/cJLZLLEfqLxjloyz1KWUuW/IAM-Risk-Overview?node-id=0-1&t=wq1ER1qyzHtA0iUl-1
