---
go_back: true
---

## Subprocessors
_(for PassFlow and DoorFlow)_

_Last updated:** 4 December 2025_

**NetNodes Limited**, trading as **PassFlow** and **DoorFlow**, relies on the following subprocessors to deliver the Service.



### 1. Hosting, Infrastructure & Networking

#### DigitalOcean, LLC
- **Purpose:** Cloud hosting, compute, storage, networking.  
- **Data processed:** Customer account data, application data, metadata, logs.  
- **Regions used:** **Amsterdam (NL)** and **London (UK)**.  
- **Transfer mechanism:** EU/UK hosting only; no international transfers.  
- **Website:** digitalocean.com



### 2. Communications (Email, SMS, Voice)

#### **Twilio, Inc.**
- **Purpose:** SMS and phone communications for system alerts and MFA (if enabled).  
- **Data processed:** Phone numbers, message content, delivery metadata.  
- **Location:** USA / global.  
- **Transfer mechanism:** SCCs + technical safeguards.  
- **Website:** twilio.com

#### SendGrid (Twilio SendGrid)
- **Purpose:** Transactional email delivery.  
- **Data processed:** Email addresses, email content, metadata.  
- **Location:** USA.  
- **Transfer mechanism:** SCCs.  
- **Website:** sendgrid.com



### 3. Application Monitoring & Logging

#### AppSignal B.V.
- **Purpose:** Application monitoring and error reporting.  
- **Data processed:** Error logs, metadata, anonymised contextual information.  
- **Location:** EU.  
- **Transfer mechanism:** No transfers outside EU.  
- **Website:** appsignal.com



### 4. Analytics

#### Matomo (self-hosted)
- **Purpose:** Privacy-respecting product analytics for PassFlow and DoorFlow.  
- **Data processed:** Pseudonymised usage metrics (IP anonymisation enabled), device type, pages visited, event data.  
- **Location:** **Hosted by NetNodes on DigitalOcean (NL/UK)**.  
- **Transfer mechanism:** *No transfers outside UK/EU. Data remains fully self-hosted by NetNodes.*  
- **Website:** matomo.org



### 5. Payments & Billing

#### Stripe Payments Europe Ltd
- **Purpose:** Subscription billing and payment processing.  
- **Data processed:** Payment information, billing details, transaction metadata.  
- **Location:** EU with controlled transfers to US.  
- **Transfer mechanism:** SCCs.  
- **Website:** stripe.com

#### PayPal (Europe) S.à r.l. et Cie, S.C.A.
- **Purpose:** Optional payment collection.  
- **Data processed:** Payment information, account metadata.  
- **Location:** EU + USA.  
- **Transfer mechanism:** SCCs.  
- **Website:** paypal.com

#### GoCardless Ltd
- **Purpose:** Bank-to-bank payments (Direct Debit).  
- **Data processed:** Bank details, payer identity, transaction metadata.  
- **Location:** UK + EU.  
- **Transfer mechanism:** SCCs where necessary.  
- **Website:** gocardless.com



### 6. Identity & Access (Enterprise SSO)

*(Used only if enabled by enterprise customers.)*

#### Microsoft Entra ID
- **Purpose:** Identity provider for SSO.  
- **Data processed:** Authentication tokens, identity profile (minimal).  
- **Location:** Customer-selected region (typically EU or UK).  
- **Transfer mechanism:** SCCs if applicable.  
- **Website:** microsoft.com

#### Google Workspace / Google Identity
- **Purpose:** Identity provider for SSO.  
- **Data processed:** Authentication tokens, identity profile.  
- **Location:** Customer tenancy settings.  
- **Transfer mechanism:** SCCs.  
- **Website:** google.com



### 7. Apple & Google Wallet Ecosystems

#### Apple Inc.
- **Purpose:** Delivery of Apple Wallet passes, updates, and push tokens.  
- **Data processed:** Device identifiers, pass metadata, update tokens.  
- **Location:** Global infrastructure.  
- **Transfer mechanism:** SCCs + Apple global compliance framework.  
- **Website:** apple.com

#### Google LLC (Google Wallet)
- **Purpose:** Delivery of Google Wallet passes and updates.  
- **Data processed:** Device identifiers, pass metadata, update tokens.  
- **Location:** Global infrastructure.  
- **Transfer mechanism:** SCCs.  
- **Website:** google.com


