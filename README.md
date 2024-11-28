# Business Email Compromise (BEC) Detection with Sublime Security

## Project Overview:
This project demonstrates the use of **Sublime Security** in detecting **Business Email Compromise (BEC)** and similar email-based threats. By leveraging advanced email inspection and behavioral analytics, Sublime Security helps organizations mitigate risks such as unauthorized access to email accounts, data theft, and phishing attacks. In this project, I tried to showcase how the tool automatically flags suspicious emails, tracks user interactions, and provides detailed insights for security analysts.


## Key Features:

### 1. **Email Inspection and Analysis**
Sublime Security's email inspection feature enables detailed analysis of flagged emails. This allows security analysts to review suspicious messages and understand the rationale behind their classification as to why it was flagged. 

- **Feature Overview:**
    - Inspect the flagged email content.
    - Review sender information, attachments, and any indicators of compromise.
    
    ![](https://i.imgur.com/YoAmcXt.png)

---

### 2. **Tracking Email Interactions**
The tool automatically tracks key interactions with emails, helping analysts understand if the email was opened, replied to, or forwarded within the organization. This feature is critical in determining the scope of potential compromises.

- **Feature Overview:**
    - Identify whether the email was opened or interacted with by the recipient.
    - Track any internal forwarding of the email that could indicate further compromise.
    
    ![](https://i.imgur.com/dtG4FoY.png)

---

### 3. **Automated Threat Scoring**
Sublime Security assigns an attack score to flagged emails based on various criteria such as message content, urgency, and suspicious attachments. The attack score helps prioritize the response to potential threats.

- **Feature Overview:**
    - Automatically assigns threat scores such as **Malicious** based on email content.
    - Provides insights into the factors influencing the attack score, such as urgency in the subject line or suspicious attachments.


    ![](https://i.imgur.com/fYm9rp8.png)
    ![](https://i.imgur.com/RCicpSk.png)
---

### 4. **Detailed Flagging Criteria**
The tool provides detailed reasons for why an email was flagged, helping security analysts understand the underlying threats.

- **Feature Overview:**
    - Explanation of why an email was flagged (e.g., short message body, suspicious language, or urgent tone).
    - Example of how the tool flags emails based on specific criteria.
    
    ![](https://i.imgur.com/3lNpYre.png)

---

### 5. **Customizable Email Filtering Rules**
Sublime Security allows organizations to define and customize email filtering rules that align with their specific security policies. This feature helps prevent unwanted emails based on predefined conditions.

- **Feature Overview:**
    - Create custom rules to block or flag emails based on file types, subject keywords, or sender attributes.
    - Allows rule adjustments based on the organization's security posture.
    
    ![](https://i.imgur.com/YoAmcXt.png)

---

### 6. **QR Code Link and URL Scanning**
Sublime Security automatically scans QR codes and URLs embedded in email attachments to detect potentially malicious links before they are clicked.

- **Feature Overview:**
    - Provides a preview of the URL embedded in QR codes, allowing analysts to evaluate links before opening them.
    - Shows detailed information about the URL, including any known threats associated with it.
    
    ![](https://i.imgur.com/YoAmcXt.png)

---

### 7. **Email Content Review for Further Investigation**
The tool enables a deeper dive into the flagged email’s message content. Analysts can review specific email elements, such as attachments, body text, and metadata, to conduct further investigations.

- **Feature Overview:**
    - Review full message content and metadata associated with the flagged email.
    - Examine attachments, headers, and any suspicious patterns in the email body.
    
    ![](https://i.imgur.com/ubSta9l.png)

    ![](https://i.imgur.com/vnthMUj.png)
---

### 8. **Mobile Device Management (MDM) Integration**
The tool provides an MDM view that enables the creation of rules specifically for mobile devices. This ensures that threats originating from mobile platforms are effectively mitigated.

- **Feature Overview:**
    - Create security rules tailored for mobile devices to prevent mobile-originated threats.
    - View mobile-specific email interactions and apply MDM policies accordingly.
    
    ![](https://i.imgur.com/wNRpgML.png)

---

### 9. **Compromise Vector Hunting**
Sublime Security allows analysts to hunt for specific file types commonly used in phishing attacks. This includes looking for email attachments with **.html**, **.htm**, or **.dhtml** extensions, which are often used in malicious campaigns.

- **Feature Overview:**
    - Automatically search for inbound emails containing attachments with specific file types such as **.html**, **.htm**, or **.dhtml**.
    - Identify and block emails that may contain dangerous file extensions before they can do damage.
    
    ![](https://i.imgur.com/PPoCS6i.png)

---

### 10. **API Integration for Automation**
Sublime Security provides API integration, allowing organizations to automate threat detection and response. This enables seamless communication between Sublime Security and other security tools or incident response platforms.

- **Feature Overview:**
    - Use API calls to automate the flagging of emails and initiate response actions.
    - Integrate with other security systems to trigger further analysis or remediation automatically.
    
    ![](https://i.imgur.com/0lA3FXE.png)



---

## Conclusion:
This project demonstrates how **Sublime Security** can enhance an organization's ability to detect and respond to **Business Email Compromise (BEC)** attacks. By leveraging automated threat scoring, email inspection, and customizable rules, organizations can improve their security posture and reduce the risk of email-based attacks.

---

## Future Enhancements:
- Extend the functionality to include more detailed reporting and analytics.
- Integrate with other **SIEM** (Security Information and Event Management) tools for broader threat intelligence.
- Implement **real-time notification systems** to alert analysts to flagged emails immediately.

---


