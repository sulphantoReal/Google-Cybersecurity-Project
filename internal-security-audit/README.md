# Internal Security Audit — Botium Toys

Part of the Google Cybersecurity Professional Certificate (Coursera).

## Overview
Conducted an internal security audit for Botium Toys, a fictional toy company, 
covering their assets, internal network, and systems. The goal was to assess 
existing security controls and compliance practices, then identify gaps against 
recognized frameworks and standards.

## Files
- `Botium_Toys__Scope__goals__and_risk_assessment_report.docx` — defines the 
  audit scope and goals, inventories current assets, and presents a risk 
  assessment with a calculated risk score
- `Controls_and_compliance_checklist.docx` — checklist assessing existing 
  security controls (e.g., firewall, encryption, access control) and 
  compliance against PCI DSS, GDPR, and SOC frameworks

## Approach
Used the NIST Cybersecurity Framework (CSF) — starting with the **Identify** 
function — to assess Botium Toys' assets and determine the impact of potential 
asset loss on business continuity. Evaluated existing controls against 
industry compliance standards (PCI DSS for payment data, GDPR for E.U. 
customer data, SOC for internal system controls).

## Key Findings
- Overall risk score: **8/10** (high), driven by missing controls and 
  incomplete compliance adherence
- Gaps identified: no encryption on stored cardholder data, no least-privilege 
  or separation-of-duties access controls, no intrusion detection system, 
  no disaster recovery plan or data backups, weak password policy with no 
  centralized enforcement
- Existing strengths: firewall in place, antivirus monitored regularly, 
  physical security controls (locks, CCTV, fire detection) adequate, 
  GDPR breach-notification process (72-hour E.U. customer notification) in place

## Key Takeaways
Practiced mapping real-world security gaps to a structured framework (NIST CSF) 
and translating findings into a risk score and actionable compliance checklist — 
core skills for an internal security audit.
