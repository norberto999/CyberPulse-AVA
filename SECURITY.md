# CyberPulse-AVA Security Policy

## Purpose

CyberPulse-AVA is an internal cybersecurity platform developed for Avara Foods.

The purpose of this document is to define the security principles, responsibilities, and operational requirements governing the use, development, and management of CyberPulse-AVA.

This platform supports Avara Foods' cyber security programme by providing visibility into user security posture, device compliance, security awareness, threat intelligence, and security guidance through AVA.

---

# Security Objectives

CyberPulse-AVA has been designed to support the following objectives:

- Improve cyber security awareness across Avara Foods
- Increase visibility of organisational security posture
- Enhance employee engagement with security initiatives
- Support compliance and governance requirements
- Assist with threat detection and risk management
- Provide actionable security insights to users and administrators

---

# Data Classification

CyberPulse-AVA may process and display information classified as:

### Internal

Information intended for Avara Foods employees.

Examples:

- Security training progress
- User CyberScores
- Device compliance information
- Security recommendations

---

### Confidential

Information restricted to authorised personnel.

Examples:

- Security incidents
- Security alerts
- Threat intelligence
- Risk assessments
- Vulnerability findings

Access to confidential information must be granted on a least-privilege basis.

---

# Access Control

CyberPulse-AVA access must be managed through approved identity providers.

### Authentication

Supported methods:

- Microsoft Entra ID
- Multi-Factor Authentication (MFA)

Local accounts should not be used in production environments.

---

### Authorisation

Access should be granted according to role requirements.

Examples:

| Role | Access Level |
|--------|-------------|
| Employee | Personal Security Information |
| Manager | Team Visibility (where approved) |
| IT Support | Device Compliance Data |
| Cyber Security Team | Full Security Operations Access |
| Platform Administrators | System Administration |

The Principle of Least Privilege must be applied at all times.

---

# Data Protection

CyberPulse-AVA must adhere to Avara Foods data protection standards.

### Data in Transit

All communications must be encrypted using HTTPS/TLS.

---

### Data at Rest

Sensitive information should be stored securely within approved systems and databases.

Where possible:

- Encryption should be enabled
- Access should be restricted
- Audit logging should be enabled

---

### Personal Data

Only data necessary for the operation of CyberPulse-AVA should be processed.

Examples:

- Name
- Department
- Role
- Device Information
- Security Awareness Status

The platform must not collect unnecessary personal information.

---

# Microsoft Security Integrations

CyberPulse-AVA integrates with Microsoft security services to support operational visibility.

Integrations may include:

- Microsoft Entra ID
- Microsoft Intune
- Microsoft Defender
- Microsoft Graph
- Microsoft Teams

Access permissions should be reviewed regularly.

Service accounts and application registrations should use the minimum permissions required.

---

# Logging and Monitoring

The platform should maintain audit logging for:

- User sign-ins
- Administrative actions
- Changes to security settings
- Integration failures
- Security-related events

Logs should be retained in accordance with Avara Foods policies and standards.

---

# Development Security Standards

All development activities should follow secure coding principles.

### Requirements

- Input validation
- Error handling
- Access control validation
- Secure configuration management
- Dependency management
- Version control through GitHub

---

### Secrets Management

The following must never be stored within source code:

- Passwords
- API Keys
- Access Tokens
- Client Secrets
- Certificates

Secrets should be stored using approved secure methods.

---

# Security Reviews

Major updates should be reviewed before deployment.

Reviews should consider:

- Access Control
- Authentication
- Data Protection
- Logging
- Integration Security
- Dependency Risks

---

# Incident Response

If a security issue affecting CyberPulse-AVA is identified:

1. Notify the Cyber Security Team.
2. Assess business impact.
3. Implement containment measures.
4. Investigate root cause.
5. Apply remediation.
6. Document lessons learned.

Critical security issues should be prioritised immediately.

---

# User Responsibilities

Users of CyberPulse-AVA are expected to:

- Use the platform responsibly
- Protect their credentials
- Report suspicious activity
- Follow Avara Foods security policies
- Complete required security awareness training

---

# Platform Ownership

CyberPulse-AVA is owned and maintained by:

### Avara Foods

Primary Stakeholders:

- Cyber Security Team
- IT Operations
- Platform Administrators

Strategic ownership remains with Avara Foods.

---

# Guiding Principles

CyberPulse-AVA has been developed around five core principles:

1. Security First
2. Simplicity for Users
3. Least Privilege Access
4. Transparency and Visibility
5. Continuous Improvement

---

## Internal Use Only

CyberPulse-AVA is an internal platform developed to support the cyber security objectives of Avara Foods and is not intended for public or commercial use.
