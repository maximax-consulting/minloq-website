# Data Processing Agreement (DPA)

**Minloq Pte. Ltd. (Data Intermediary) and the Customer (Organisation)**

**Version 2.0 — effective 16 July 2026**
*Supersedes Version 1.0 (25 June 2026).*

---

## 1. Parties and roles

1.1 This Agreement is between **Minloq Pte. Ltd.** (UEN 202615062H) ("Minloq")
and the customer organisation that accepts it at onboarding ("Customer").

1.2 Under the Singapore Personal Data Protection Act 2012 ("PDPA"), the
Customer is responsible for the personal data it submits to the platform.
Minloq acts as a **data intermediary**, processing personal data only on the
Customer's documented instructions, including those instructions inherent in
the Customer's use of the platform.

## 2. Scope and purpose

2.1 Minloq processes personal data solely to provide the services **active on
the Customer's plan**, which may include bookkeeping, GST, corporate-secretarial
and know-your-client (KYC/CDD), payroll, and financial-statement services.

2.2 **Service activation.** This Agreement describes the full scope of the
Minloq platform. A service processes personal data only once it is **active for
the Customer**. Services not yet released, or not included in the Customer's
plan, process no personal data. Where a service is described below as *not yet
active*, the corresponding data subjects and data categories are out of scope
until activation, at which point the same principles in this Agreement apply.

2.3 **Data subjects**, by service:

| Service | Data subjects | Status |
|---|---|---|
| Bookkeeping / GST | The Customer's staff and authorised users; the Customer's customers and suppliers named in documents submitted to the platform | **Active** |
| Financial statements | As above | **Active** |
| Corporate-secretarial / KYC-CDD | Directors, shareholders, beneficial owners, and other individuals identified in due-diligence materials | **Not yet active** |
| Payroll | The Customer's employees | **Not yet active** |

2.4 **Data categories**, by service:

(a) **Bookkeeping, GST and financial statements (active):** names and contact
details; bank and payment details; and personal data incidentally contained in
uploaded documents or messages.

(b) **Corporate-secretarial / KYC-CDD (not yet active):** identification data
including NRIC or FIN, passport number, nationality, country of birth, date of
birth, gender and alias names; and the results of politically-exposed-person and
sanctions screening.

(c) **Payroll (not yet active):** identification data including NRIC or FIN;
salary and bank account details; immigration and work-pass status; and — **only
where required to calculate statutory contributions to Singapore self-help
groups (CDAC, MBMF, SINDA and ECF)** — the employee's ethnic group and, for
MBMF, religious affiliation.

2.5 **Sensitive data handling.**

(a) **NRIC/FIN.** The corporate-secretarial/KYC-CDD and payroll services are not
yet active and no NRIC or FIN is currently stored. Before either service is
activated for any Customer, NRIC and FIN data will be stored in encrypted form,
masked by default in the platform display, and unmaskable only through
controlled, access-restricted and logged actions. Minloq follows the PDPC's
guidance on the collection and use of NRIC numbers.

(b) **Ethnic group and religious affiliation.** Where collected under clause
2.4(c), this data is used **solely** to calculate and report statutory self-help
group contributions as required by Singapore law. It is not used for any other
purpose, is not disclosed except as required for those statutory contributions,
and is subject to the same encryption, masking and access controls as NRIC data.
Employees may opt out of self-help group contributions in accordance with the
relevant fund's rules.

(c) **Screening results.** Where collected under clause 2.4(b), screening
results are proposals for a qualified professional to review and conclude.
Minloq does not make or record a final risk determination on any individual.

## 3. Customer obligations

3.1 The Customer warrants that it has a lawful basis to submit the personal data
and to authorise its processing by Minloq.

3.2 The Customer is responsible for the accuracy of the data it submits and for
obtaining any consents required from data subjects, including from its staff,
customers, suppliers and employees.

## 4. Minloq obligations

4.1 Minloq processes personal data only on the Customer's documented
instructions, including those inherent in platform use.

4.2 Minloq's personnel with access to personal data are bound by confidentiality
obligations.

4.3 Minloq implements the security measures described in Schedule B.

4.4 **No sale of data.** Minloq does not sell the Customer's personal data.

4.5 **No model training on Customer data.** The Customer's personal data is not
used to train third-party or foundation AI models; Minloq's AI processing is
performed through providers (such as AWS Bedrock) whose terms do not use
customer content to train their underlying models. Where Minloq improves
suggestions based on the Customer's prior categorisations, that learning is
applied **within the Customer's own account**.

## 5. Sub-processors (Schedule A)

5.1 The Customer authorises Minloq to engage the sub-processors listed in
Schedule A. Minloq remains responsible for their compliance with this Agreement.

5.2 Minloq will give the Customer reasonable advance notice of the addition or
replacement of a sub-processor and a reasonable period to object.

## 6. International transfer

6.1 Minloq's **core data** — the Customer's books, uploaded documents, and
primary AI processing — is stored and processed in **Singapore** (Supabase
Singapore region; Amazon Web Services ap-southeast-1).

6.2 Certain **ancillary services** are operated by established global providers
that process limited data outside Singapore, and whose processing region the
Customer and Minloq cannot select:

- Transactional email delivery (Resend);
- Subscription billing — billing and contact data only, not the Customer's books (Stripe);
- WhatsApp messaging transport for document intake (Meta Platforms);
- SMS one-time-passcode verification (Twilio);
- Rate-limiting metadata (Upstash).

6.3 Where personal data is transferred outside Singapore through these ancillary
services, Minloq relies on the transfer safeguards and data-protection terms
offered by each provider. Core financial data is Singapore-resident; limited
ancillary transport, billing, verification and email data is handled by global
providers under transfer safeguards.

## 7. Data breach notification

7.1 Minloq will notify the Customer without undue delay after becoming aware of a
data breach affecting the Customer's data, and will provide the information the
Customer reasonably needs to meet its own obligations under the PDPA's data-breach
notification regime.

## 8. Data subject rights

8.1 Minloq will, where technically feasible, assist the Customer in responding to
access and correction requests made by data subjects under the PDPA.

## 9. Retention and deletion

9.1 On termination, Minloq will make the Customer's data available for **export in
a commonly-used format**, and will then **delete or return** the Customer's data
within **30 days**, **subject to any retention required by law** (including
statutory accounting and tax record-keeping obligations, which under IRAS guidance
are generally five years and which may override a deletion request).

9.2 Minloq's platform uses a soft-delete model that preserves the audit trail and
does not hard-delete accounting records. Deletion under this clause is effected by
removal of access and soft-deletion, subject to the statutory retention in clause
9.1.

## 10. Audit

10.1 Minloq will make available the information reasonably necessary to demonstrate
its compliance with this Agreement.

## 11. Liability and term

11.1 To the maximum extent permitted by Singapore law, Minloq's total aggregate
liability arising out of or in connection with this Agreement is **limited to the
total fees paid by the Customer to Minloq in the twelve (12) months preceding the
event giving rise to the claim**.

11.2 To the maximum extent permitted by law, Minloq is not liable for indirect,
incidental, special or consequential loss, or for loss of profits, revenue,
goodwill or data.

11.3 Nothing in this Agreement excludes or limits liability that cannot be excluded
or limited under Singapore law, including liability for fraud, fraudulent
misrepresentation, or wilful misconduct, or any of Minloq's non-excludable
statutory obligations as a data intermediary under the PDPA.

11.4 This Agreement applies for as long as Minloq processes personal data on the
Customer's behalf and is read together with Minloq's Terms of Service.

## 12. Governing law

12.1 This Agreement is governed by the laws of Singapore, and the parties submit to
the non-exclusive jurisdiction of the Singapore courts.

## 13. Severability

13.1 If any provision of this Agreement is held to be invalid or unenforceable,
that provision is severed to the minimum extent necessary and the remaining
provisions continue in full force and effect.

## 14. Contact and Data Protection Officer

14.1 Minloq's Data Protection Officer can be contacted at **hello@minloq.sg** for
questions about this Agreement or about how Minloq handles personal data.

---

## Schedule A — Sub-processors

*Schedule A is maintained as a living list under clause 5.2. The current
list, with its change history, is published at minloq.sg/subprocessors (the
canonical source; this Schedule renders it). Additions take effect per
clause 5.2 notice and are never applied to an account retroactively.*

**Platform sub-processors** (process the Customer's client / financial data):

| Sub-processor | Purpose | Processing location |
|---|---|---|
| Amazon Web Services | AI extraction (Bedrock), OCR (Textract) | Singapore (ap-southeast-1) |
| Supabase | Database and file storage | Singapore region |
| Vercel | Application hosting and serverless API routes | Serverless functions: Singapore (sin1); static assets served via global edge network |
| Meta Platforms | WhatsApp Cloud API — messaging intake | Outside Singapore |
| Telegram Messenger Inc. † | Telegram Bot API — document intake: photos and files sent to a connected Telegram group | Outside Singapore |
| Resend | Transactional email | Outside Singapore |
| Stripe | Subscription billing (billing/contact data only, not the Customer's books) | Outside Singapore |
| Twilio | SMS one-time-passcode verification only (not WhatsApp) | Outside Singapore |
| Upstash | Rate-limiting metadata (tenant identifier / IP address); no document or financial content | Outside Singapore |

† Added August 2026 under clause 5.2 — off by default; active for an account
only after that account consents or its notice period ends without objection.
Change history: minloq.sg/subprocessors.

**Website sub-processor** (processes prospect data at minloq.sg, not the
Customer's books):

| Sub-processor | Purpose | Processing location |
|---|---|---|
| Formspree | Contact and signup form submissions | Outside Singapore |

## Schedule B — Security measures

- Tenant isolation via row-level security (RLS) on all data tables
- Singapore data residency for core data (database, file storage, primary AI processing)
- Encryption in transit (HTTPS / TLS)
- Encryption at rest on the database and file storage
- Multi-factor authentication available for portal access
- Soft-delete model preserving the audit trail; no hard deletion of accounting records
- Audit logging of document and data actions
- Static analysis (SAST) in the development pipeline
- Field-level encryption, default masking and logged unmasking for NRIC/FIN and
  payroll-sensitive data — to be in place before the corporate-secretarial/KYC-CDD
  and payroll services are activated (clause 2.5)

---

*Version 2.0 — effective 16 July 2026. Minloq Pte. Ltd. (UEN 202615062H),
Singapore. Data Protection Officer: hello@minloq.sg.*
