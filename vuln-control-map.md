**Document Type:** Compliance & Control Mapping Standard\
**Domain:** Vulnerability Management / GRC\
**Version:** 1.0\
**Owner:** CISO Office / Governance, Risk & Compliance (GRC)\
**Effective Date:** \[Insert Date\]

**1. Purpose**

This document establishes a standardized mapping of **Vulnerability
Management controls** to leading industry frameworks, ensuring alignment
with regulatory requirements and enabling **audit readiness and control
traceability**.

**2. Scope**

This mapping applies to:

- Infrastructure vulnerability management

- Cloud and container security

- Application vulnerability management (where applicable)

- Enterprise-wide security controls

**3. Objectives**

- Align VM controls with global standards

- Provide clear control traceability for audits

- Enable unified compliance reporting

- Standardize evidence collection

**4. Frameworks Covered**

This document maps controls to the following frameworks:

- NIST Cybersecurity Framework (CSF)

- ISO 27001:2022

- PCI Security Standards Council PCI DSS v4.0

**5. Control Mapping Methodology**

**5.1 Mapping Principles**

- One-to-many mapping (single control mapped to multiple frameworks)

- Control normalization to avoid duplication

- Focus on **intent alignment**, not just wording

- Evidence-driven validation

**5.2 Control Domains (VM Program)**

| **Domain**                   | **Description**                   |
|------------------------------|-----------------------------------|
| Asset Discovery              | Identification of assets in scope |
| Vulnerability Identification | Scanning and detection            |
| Risk Prioritization          | Risk-based scoring                |
| Remediation                  | Patch and fix processes           |
| Validation                   | Re-scan and verification          |
| Reporting                    | Metrics and dashboards            |
| Exception Management         | Risk acceptance                   |
| Continuous Monitoring        | Ongoing assessment                |

**6. Control Mapping Table**

**6.1 Sample Control Mapping**

| **Control ID** | **Control Description** | **NIST CSF** | **ISO 27001** | **PCI DSS v4.0** | **Evidence Required** |
|----|----|----|----|----|----|
| VM-01 | Asset inventory maintained and updated | ID.AM-1 | A.5.9 | Req 2.4 | CMDB export, asset reports |
| VM-02 | Regular vulnerability scanning performed | DE.CM-8 | A.12.6.1 | Req 11.3.1 | Scan reports, schedules |
| VM-03 | Risk-based vulnerability prioritization | ID.RA-5 | A.5.7 | Req 6.3.1 | Risk scoring model |
| VM-04 | Timely remediation of vulnerabilities | RS.MI-3 | A.8.8 | Req 6.2 | Patch reports, tickets |
| VM-05 | Re-scan validation post remediation | DE.CM-8 | A.12.6.1 | Req 11.3.1 | Re-scan evidence |
| VM-06 | SLA defined and enforced | PR.IP-12 | A.5.36 | Req 6.3.3 | SLA policy, reports |
| VM-07 | Exception management process | ID.RA-6 | A.5.35 | Req 6.3.3 | Exception approvals |
| VM-08 | Continuous monitoring of vulnerabilities | DE.CM-1 | A.8.16 | Req 11.5 | SIEM dashboards |

**7. Control Definitions**

Each control must include:

**7.1 Control Description**

Clear definition of control objective and requirement

**7.2 Control Owner**

- VM Team

- IT Operations

- Security Operations

**7.3 Frequency**

- Continuous / Weekly / Monthly

**7.4 Control Type**

- Preventive

- Detective

- Corrective

**8. Evidence Mapping**

**8.1 Evidence Categories**

| **Evidence Type**      | **Examples**        |
|------------------------|---------------------|
| System Evidence        | Scan reports, logs  |
| Process Evidence       | SOPs, runbooks      |
| Ticket Evidence        | ITSM records        |
| Configuration Evidence | Tool configurations |

**8.2 Evidence Requirements**

Each control must have:

- Defined evidence type

- Storage location (e.g., SharePoint, GRC tool)

- Retention period (e.g., 1 year minimum)

**8.3 Sample Evidence Mapping**

| **Control ID** | **Evidence Type** | **Source**     | **Frequency** | **Owner** |
|----------------|-------------------|----------------|---------------|-----------|
| VM-02          | Scan Report       | Qualys/Tenable | Weekly        | VM Team   |
| VM-04          | Patch Ticket      | ServiceNow     | Continuous    | IT Ops    |
| VM-07          | Exception Record  | GRC Tool       | As needed     | Risk Team |

**9. Audit & Compliance Usage**

- Supports internal and external audits

- Provides traceability from control → evidence

- Enables rapid audit response

- Reduces compliance duplication across frameworks

**10. Integration with GRC Tools**

- Integration with tools such as ServiceNow GRC / Archer

- Automated evidence collection where possible

- Control status tracking (Effective / Ineffective)

**11. Reporting**

- Control effectiveness dashboard

- Compliance status by framework

- Audit readiness status

**12. Governance**

- Reviewed annually or upon framework updates

- Approved by CISO and Compliance टीम

- Maintained by GRC function

**13. Continuous Improvement**

- Update mappings for new framework versions

- Enhance automation of evidence collection

- Align with evolving threat landscape

**14. Appendices**

**Appendix A – Full Control Mapping Matrix**

**Appendix B – Evidence Collection Checklist**

**Appendix C – Audit Preparation Guide**

**End of Document**
