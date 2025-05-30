# 02 - IAAA Principles

## 📘 Overview

Today’s lesson introduced the **IAAA model**, which extends beyond the CIA Triad to define how access control and user accountability are enforced in cybersecurity. The four components are:

- **Identification**
- **Authentication**
- **Authorization**
- **Accountability**

---

### 🆔 Identification
- **Definition**: The process of claiming an identity. This usually involves providing a username, user ID, or another unique identifier.
- **Purpose**: Allows the system to recognize "who" is requesting access.

---

### 🔐 Authentication
- **Definition**: Verifying that a user is who they claim to be.
- **Types**:
  - **Type 1**: Something you know (e.g., passwords, PINs)
  - **Type 2**: Something you have (e.g., ID card, smartphone token)
  - **Type 3**: Something you are (e.g., biometrics like fingerprints or facial recognition)
- **Security Best Practices**:
  - Credentials should be **unpredictable**.
  - Use **clipping levels**: a limit on login attempts to protect against brute-force attacks.

---

### 🔓 Authorization
- **Definition**: Granting access to system resources based on the authenticated user's permissions.
- **Models**:
  - **RBAC (Role-Based Access Control)**: Access is based on user roles.
  - **DAC (Discretionary Access Control)**: Resource owners decide access permissions.
  - **MAC (Mandatory Access Control)**: Access is based on predefined policies and classification levels.
- **Subjects vs Objects**:
  - **Subject**: The user or process requesting access.
  - **Object**: The resource being accessed (e.g., files, databases, programs).

---

### 🧾 Accountability
- **Definition**: Ensuring that all actions taken on a system can be traced back to a specific user or process.
- **Tools**:
  - System logs
  - Audit trails
  - Session tracking
- **Purpose**: Supports non-repudiation and helps in identifying misuse or attacks.

---

## 🧠 Key Takeaways

- **IAAA** is critical for building secure access control mechanisms in any system.
- Authentication is only meaningful if paired with proper **authorization** and **accountability**.
- Biometric authentication (Type 3) offers the highest level of identity assurance.

---

## 📅 Session Info

- **Date**: May 29, 2025  
- **Course**: *The Complete Certified in Cybersecurity (CC) - ISC2 2025*  
- **Module**: 01 - Security Principles > 02 - IAAA

