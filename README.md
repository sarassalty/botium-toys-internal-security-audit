# Summary of the activity <a name="Summary"></a>
This is an intern audit about a fictional factory called **Botium Toys**. This is part of my formation in [Google's Cybersecurity Professional Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity) . My task is to review the project scope, objectives, and the IT responsible's risk assessment report. Subsequently, carry out an internal audit by completing a comprehensive control and compliance checklist.


## Scenario 
Botium Toys is a small US-based company that develops and sells toys. The company has a single physical location, serving as its headquarters, showroom, and warehouse for its products. However, Botium Toy's online presence has grown, attracting customers both domestically and internationally. As a result, its Information Technology (IT) department is under increasing pressure to support its worldwide online market.

The IT director has determined that an internal IT audit is necessary. She is concerned about maintaining compliance and business operations as the company grows without a clear plan. She believes that an internal audit can help better protect the company's infrastructure and assist them in identifying and mitigating potential risks, threats, or vulnerabilities to critical assets. The executive is also interested in ensuring that they comply with regulations related to internal processing and acceptance of online payments and conducting business in the European Union (EU).

The IT responsible begins by applying the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), establishing an audit scope and objectives, listing the assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or 1  penalties the company could experience due to the current state of its security posture.


### Audit Scope and Goals
**Scope:** The internal IT audit will assess the following: <br>
+ Assess user permissions 
+ Identify existing controls, procedures, and system protocols 
+ Account for technology currently in use 

**Goals:** The goals for the internal IT audit are: 
+ Adhere to the NIST Cybersecurity Framework (CSF) 
+ Establish policies and procedures to ensure compliance with regulations 
+ Fortify system controls 

### Current assets
Assets managed by the IT Department include: <br>
+ On-premises equipment for in-office business needs 
+ Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc. 
+ Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse 
+ Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management 
+ Internet access 
+ Internal network 
+ Data retention and storage 
+ Legacy system maintenance: end-of-life systems that require human monitoring
  
### Risk assessment

**Risk description** <br>
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. <br>

**Control best practices** <br>
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.<br>

**Risk score** <br>
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices. <br>

**Additional comments** <br>
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details: <br>

+ Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII. 
+ Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
+ Access controls pertaining to least privilege and separation of duties have not been implemented. 
+ The IT department has ensured availability and integrated controls to ensure data integrity. 
+ The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules. 
+ Antivirus software is installed and monitored regularly by the IT department. 
+ The IT department has not installed an intrusion detection system (IDS). 
+ There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
+ The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data. 
+ Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
+ There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password. 
+ While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear. 
+ The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems. 


## Controls and compliance checklist

### Controls assessment checklist
Select “yes” or “no” to answer the question: Does Botium Toys currently have this control in place? 

| Control                              | Status      | 
|--------------------------------------|-------------|
| **Less Privileged**                  | ❌ No       | 
| **Disaster Recovery Plans**          | ❌ No       |
| **Password Policies**                | ❌ No       | 
| **Separation of Duties**             | ❌ No       | 
| **Firewall**                         | ✅ Yes      | 
| **Intrusion Detection System (IDS)** | ❌ No       |
| **Backups**                          | ❌ No       | 
| **Antivirus Software**               | ✅ Yes      | 
| **Manual Monitoring System**         | ❌ No       | 
| **Encryption**                       | ❌ No       | 
| **Password Management System**       | ❌ No       |
| **Locks (offices, storefront, warehouse)**| ✅ Yes | 
| **Closed-circuit television (CCTV) surveillance**|✅ Yes| 
| **Fire detection/prevention (fire alarm, sprinkler system, etc.)**| ✅ Yes      | 

### Compliance checklist
Select “yes” or “no” to answer the question: Does Botium Toys currently adhere to this compliance best practice?

**Payment Card Industry Data Security Standard (PCI DSS)**

| Practice                                                                 | Status      | 
|--------------------------------------------------------------------------|-------------|
| Only authorized users have access to customers’ credit card information. | ❌ No       | 
| Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | ❌ No     | 
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. | ❌ No       |
| Adopt secure password management policies.         | ❌ No       | 

### General Data Protection Regulation (GDPR)

| Practice                                            | Status      |  
|-----------------------------------------------------|-------------|
| E.U. customers’ data is kept private/secured.       | ❌ No       | 
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach.| ✅ Yes      | 
| Ensure data is properly classified and inventoried. | ❌ No       | 
| Enforce privacy policies, procedures, and processes to properly document and maintain data.                      | ✅ Yes      | 

### System and Organizations Controls (SOC type 1, SOC type 2) 

| Practice                                          | Status      |
|---------------------------------------------------|-------------|
| User access policies are established              |  ❌ No       | 
| Sensitive data (PII/SPII) is confidential/private |  ❌ No       | 
| Data integrity ensures data is consistent, complete, accurate, and validated | ✅ Yes | 
| Data is available to individuals authorized to access it | ❌ No | 

## Recommendations <a name="recommendations">
To mitigate high-risk exposure, Botium Toys must intensify its security posture by prioritizing asset management, access controls, encryption, disaster recovery, and intrusion detection systems. This will enhance compliance with PCI DSS, GDPR, and NIST CSF standards, protecting critical operations and customer data.
