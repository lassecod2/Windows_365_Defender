# Microsoft 365 Defender
## Sentinel
![Pasted image 20211104103852.png]https://github.com/lassecod2/Windows_365_Defender/blob/main/Pasted%20image%2020211104103852.png

## The anatomy of an attack
Microsoft 365 Defender is a Cloud-based, unified, pre- and post-breach enterprise defense suite. It coordinates _prevention_, _detection_, _investigation_, and _response_ across endpoints, identities, apps, email, collaborative applications, and all of their data.

In this illustration an attack is underway. Phishing email arrives at the Inbox of an employee in your organization, who unknowingly opens the email attachment. This installs malware, which leads to a chain of events that could end with the theft of sensitive data. But in this case, Defender for Office 365 is in operation.

![[Pasted image 20211104105147.png]]

In the illustration:

-   **Exchange Online Protection**, part of Microsoft Defender for Office 365, can detect the phishing email and use mail flow rules to make certain it never arrives in the Inbox.
-   **Defender for Office 365** safe attachments tests the attachment and determines it is harmful, so the mail that arrives either isn't actionable by the user, or policies prevent the mail from arriving at all.
-   **Defender for Endpoint** manages devices that connect to the corporate network and detect device and network vulnerabilities that might otherwise be exploited.
-   **Defender for Identity** takes note of sudden account changes like privilege escalation, or high-risk lateral movement. It also reports on easily exploited identity issues like unconstrained Kerberos delegation, for correction by the security team.
-   **Microsoft Cloud App Security** notices anomalous behavior like impossible-travel, credential access, and unusual download, file share, or mail forwarding activity and reports these to the security team.

### Microsoft 365 Defender components

Microsoft 365 Defender is made up of these security technologies, operating in tandem. You don't need all of these components to benefit from the capabilities of XDR and Microsoft 365 Defender. You will realize gains and efficiencies through using one or two as well.

MICROSOFT 365 DEFENDER COMPONENTS

Component

Description

Reference material

Microsoft Defender for Identity

Microsoft Defender for Identity uses Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.

[What is Microsoft Defender for Identity?](https://docs.microsoft.com/en-us/defender-for-identity/what-is)

Exchange Online Protection

Exchange Online Protection is the native cloud-based SMTP relay and filtering service that helps protect your organization against spam and malware.

[Exchange Online Protection (EOP) overview - Office 365](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/overview?view=o365-worldwide)

Microsoft Defender for Office 365

Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs) and collaboration tools.

[Microsoft Defender for Office 365 - Office 365](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/overview?view=o365-worldwide)

Microsoft Defender for Endpoint

Microsoft Defender for Endpoint is a unified platform for device protection, post-breach detection, automated investigation, and recommended response.

[Microsoft Defender for Endpoint - Windows security](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint?view=o365-worldwide)

Microsoft Cloud App Security

Microsoft Cloud App security is a comprehensive cross-SaaS solution bringing deep visibility, strong data controls, and enhanced threat protection to your cloud apps.

[What is Cloud App Security?](https://docs.microsoft.com/en-us/cloud-app-security/what-is-cloud-app-security)

Azure AD Identity Protection

Azure AD Identity Protection evaluates risk data from billions of sign-in attempts and uses this data to evaluate the risk of each sign-in to your environment. This data is used by Azure AD to allow or prevent account access, depending on how Conditional Access policies are configured. Azure AD Identity Protection is licensed separately from Microsoft 365 Defender. It is included with Azure Active Directory Premium P2.









