<h1>Conduct a security audit (fictional scenario)</h1>

 ### [YouTube Demonstration](https://youtu.be/URL)

<h2>Description</h2>

<p>This scenario was completed during the Google Cybersecurity Certificate Program and is based on a fictional company:</p>

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 
<br />


<h2>Documentation provided</h2>

- <b>Control categories</b>
- <b>Scope, goals, and risk assessment report</b>
- <b>Control and compliance checklist</b>

<h2>Project walk-through:</h2>

<p align="center">
1. Complete the Controls assessment checklist by selecting whether Botium Toys has this control in place (Yes/No): <br/>
<img src="https://imgur.com/1cEGunm.png" height="80%" width="80%"/>
<br />
<br />
2. Complete the Compliance checklist by selecting whether Botium Toys currently adheres to this compliance best practice (Yes/No):  <br/>
<img src="https://imgur.com/YFLQx7R.png" height="80%" width="80%"/>
<img src="https://imgur.com/5EscinF.png" height="80%" width="80%"/>
<br />
<br />

Provide a recommendation to the IT Manager: <br/>
<br />
<strong>Summary:</strong> <br />
Botium Toys' needs multiple controls to improve its security and safeguard sensitive data. This includes implementing Least Privilege, disaster recovery plans, password policies, separation of duties, an IDS (Intrusion Detection System), ongoing legacy system management, encryption, and a password management system.

In addition, compliance gaps demand immediate action. Least privilege, separation of duties, and encryption are priority controls. Additionally, proper asset classification will reveal further controls necessary to bolster security and shield sensitive information.

<strong>Recommended Controls to Implement:</strong><br />
<ul>
<li>Least privilege - Unrestricted access to customer data puts us at risk of a breach. It's crucial to limit employee privileges based on their specific roles and responsibilities.</li>
<li>Disaster recovery plans - The absence of disaster recovery plans is a critical gap in our security posture. These need to be implemented to ensure business continuity.</li>
<li>Password policies - Employee password requirements are minimal, a threat actor can easily infiltrate our systems through employee devices and steal customer data, disrupt operations, or even cause financial damage.</li>
<li>Separation of duties - the current practice of the CEO handling both daily operations and payroll management presents a potential risk for fraud or inappropriate access to sensitive data. Implementing separation of duties will mitigate this risk.</li>
<li>Intrusion detection system (IDS) - The IT department needs an IDS in place to help identify possible intrusions by threat actors.</li>
<li>Backups - The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity.</li>
<li>Manual monitoring, maintenance, and intervention for legacy systems - The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task and procedures/ policies related to intervention are unclear. By implementing a regular maintenance schedule with clear procedures for intervention, we can significantly improve the security and stability of our legacy systems. </li>
<li>Encryption - Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information.
<li>Password management system - There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues.</li>
</ul>

<strong>(PCI DSS) Compliance flags:</strong><br />
Currently, all employees have access to the company’s internal data.
Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information.
The company does not currently use encryption to better ensure the confidentiality of customers’ financial information.
Password policies are nominal and no password management system is currently in place.

<strong>(GDPR) Compliance flags:</strong><br />
The company does not currently use encryption to better ensure the confidentiality of customers’ financial information.
Current assets have been inventoried/listed, but not classified.

<strong>(SOC type 1, SOC type 2) Compliance flags:</strong><br />
Controls of Least Privilege and separation of duties are not currently in place; all employees have access to internally stored data.
Encryption is not currently used to better ensure the confidentiality of PII/SPII.
While data is available to all employees, authorization needs to be limited to only the individuals who need access to it to do their jobs.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
