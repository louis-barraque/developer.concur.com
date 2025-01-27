---
title: SAP Concur Developer Center - Announcements
layout: reference
---
### 2019-10-03 :: Support for TLS v1.1 Encryption Protocol to End in First Quarter of 2020

#### Overview

SAP Concur is announcing an end-of-support cycle for version 1.1 of the Transport
Layer Security (TLS) encryption protocol, while continuing support for the more
secure version 1.2 of TLS. As background, the TLS protocol allows secure back and
forth communications between a phone or computer and a cloud-based service.

This change is currently planned for the first quarter of 2020.

##### BUSINESS PURPOSE / CLIENT BENEFIT

SAP Concur is taking this step after careful consideration of our customers’ security and ease of upgrade to the newer, more secure version 1.2 of TLS. This end-of support plan for TLS v1.1 ensures our clients are communicating with SAP Concur
solutions in a safer and more secure manner using TLS v1.2.

#### What the Customer Sees

If the customer or user ensures they are using a TLS v1.2-compliant browser, there
will be no change in the way users interact with SAP Concur. If the browser is not
compliant, users may not be able to sign in to SAP Concur.

In general, the use of less-secure TLS connections can lead to exposed data,
resulting in compromised sessions across any TLS channel of communication (for
example, SAP Concur services). For this reason, SAP Concur is alerting the client now to ensure they may anticipate this change and begin assessment in order to comply with this change at their companies.

##### AFFECTED DEVICES

In general, browsers using TLS to establish inbound / outbound communication
channels with SAP Concur services are affected, for example connections across:

* Users attempting to log in to SAP Concur solutions
* APIs
* Bulk upload via SFTP
* Connectors
* FTP / PGP
* SAP Integrations
* Other

The ability of a browser to comply by upgrade to TLS v1.2 will depend on the
company’s support for the specific browser, for example Microsoft (Edge), Google
(Chrome), and others.

##### INFORMATIONAL BANNER TO DISPLAY

A banner will display when a user attempts to log in using a browser that does not
support TLS v1.2 and later and thus cannot negotiate a connection. The intent is to
alert the user to this upcoming change using an informational-only message.

#### Configuration / Feature Activation

Transitioning to support for TLS v1.2 and later may simply require updating security settings of your browser. In most instances, the company already has the support in place and need only identify non-compliant browsers and upgrade these user’s browsers to newer versions.

Please check with the department in your company that is responsible for browser
compliance and ensure they are aware of this upcoming change.

### 2019-09-20 :: September 2019 Release Notes Published

SAP Concur has published release notes for the Quick Expense v3, Quick Expense v4, Budget v4, Reports v3, and Request APIs in the September 2019 release notes. More details can be found on the [Release Notes](https://developer.concur.com/tools-support/release-notes/index.html) page.

### 2019-05-31 :: June 2019 Release Notes Published

SAP Concur has published release notes for the Quick Expense v3, Quick Expense v4, Budget v4, and Invoice Pay v4 APIs in the June 2019 release notes. More details can be found on the [Release Notes](https://developer.concur.com/tools-support/release-notes/index.html) page.

### 2019-05-09 :: Expense API Release Notes Published

SAP Concur has published release notes for the Quick Expense v3 and Quick Expense v4 APIs in the May 2019 release notes. More details can be found on the [Release Notes](https://developer.concur.com/tools-support/release-notes/index.html) page.

### 2019-04-08 :: SAP Concur Developer Center Forum Retirement

SAP Concur will be retiring the Developer Forum on the SAP Concur Developer Center on April 14, 2019. All developers building an integration with the SAP Concur platform should contact their assigned SAP Concur technical contacts with questions.

Clients who need assistance related to an App Center Partner app should first contact the Partner's Support team. The Partner will then contact the SAP Concur Support team if they need assistance. [Support Options](https://developer.concur.com/tools-support/support.html)

Clients who need assistance related to their own external App should contact SAP Concur Support.

### 2019-03-05 :: New SSL Certificate for concursolutions.com

#### Overview
In an effort to ensure the ongoing security of our products and services, SAP Concur has issued a new concursolutions.com SSL certificate. ***The current certificate will expire on March 16, 2019.***

Any customer who has pinned this expiring certificate will need to update to the new certificate prior to March 16, 2019. If the pinned certificate is not updated prior to March 16, 2019, your organization and users will experience disruption to SAP Concur products and services.

Customers who have not pinned the certificate do not need to take any action as the new certificate is updated automatically. Most customers do not pin the certificate.

**Please be aware:** As an enhancement to our Security and Compliance program, this certificate will be updated on an annual basis.

##### BUSINESS PURPOSE / CLIENT BENEFIT

This update provides ongoing security for our products and services.

#### Configuration / Feature Activation

Please consult with your IT department to check if this applies to you.

The new SSL certificate can be accessed here: [http://assets.concur.com/concurtraining/cte/en-us/concursolutions.cert.pem](http://assets.concur.com/concurtraining/cte/en-us/concursolutions.cert.pem)

Supply this URL to your IT department.

To save the certificate, click the link above, select all the text in the browser, copy it to a file, then name the file concursolutions.cert.pem.
