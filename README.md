# Activity Overview

This project documents the cybersecurity assignment: *Determine Appropriate Data Handling Practices*. It focuses on internal access control failures and applying the principle of least privilege to prevent confidential information leaks.

The task involved analyzing a real-world incident involving premature access permissions, evaluating the root causes, and proposing security control enhancements based on **NIST SP 800-53: AC-6** and CSF standards.

## Scenario

You work for an educational technology company that developed an application to help teachers automatically grade assignments. The application handles a wide range of data that it collects from academic institutions, instructors, parents, and students.

Your team was alerted to a data leak of internal business plans on social media. An investigation by the team discovered that an employee accidentally shared those confidential documents with an external business partner. An audit into the leak is underway to determine how similar incidents can be avoided.

A supervisor provided you with information regarding the leak. It appears that the principle of least privilege was not observed by employees at the company during a sales meeting. You have been asked to analyze the situation and find ways to prevent it from happening again.

First, you'll need to evaluate details about the incident. Then, you'll review the controls in place to prevent data leaks. Next, you'll identify ways to improve information privacy at the company. Finally, you'll justify why you think your recommendations will make data handling at the company more secure.

## What’s Included

- Root cause analysis and control recommendations  
- Reflection on least privilege applications and auditing practices

---

## My Contributions

- Identified two core causes: non-revoked access and link mismanagement  
- Addressed the access control issue using **NIST SP 800-53: AC-6**, recommending:
  - Role-based restrictions on internal folders  
  - Regular audits of user privileges  
- Emphasize steps and improved planning around confidential material sharing

## Data Leak Worksheet

This writeup analyzes a real-world incident involving internal folder access, where the failure to revoke permissions led to a confidential data leak. It applies NIST SP 800-53 AC-6 and CSF PR.DS-5 to propose remediation strategies rooted in least privilege principles.

| Section             | Content                                                                                         |
|---------------------|-------------------------------------------------------------------------------------------------|
| **Incident Summary** | A sales manager shared a folder with internal-only documents during a team meeting. Although the team was warned not to redistribute the promotional materials, access remained live. During a video call with an external business partner, a team member mistakenly shared the folder link. The partner later posted the link publicly, believing the content was approved for external use. |
| **Control Identified** | Violated control: **AC-6 — Least Privilege**. This highlights the need to limit access strictly to operational necessity, and revoke permissions promptly after use. |
| **Issues Observed** | Primary breakdowns included: (1) lack of access revocation

---

## Reflection

This activity solidified the importance of both technical and procedural safeguards in preventing internal data leaks. By applying NIST’s control enhancements, I demonstrated the capacity to assess incident risk, apply structured controls, and incorporate preventative planning — core competencies in risk mitigation and policy alignment within cybersecurity frameworks.

## Screenshot of Completed Spreadsheet
![Home Asset Inventory](images/home-asset-inventory.png)
> This image captures the full response submitted as part of the Google Cybersecurity Certificate incident report activity. 
