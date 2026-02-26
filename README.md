CS 305 – Artemis Financial Security Project

Overview



This repository contains my completed security review and secure software implementation for Artemis Financial, a fictional financial services company. The goal of this project was to assess software vulnerabilities, implement secure coding practices, and strengthen the overall security posture of the application.



Included in this repository:



Spring Boot REST service application



HTTPS configuration using a keystore



OWASP Dependency-Check analysis



Completed Vulnerability Assessment Report (Project One artifact)



Client Summary



Artemis Financial is a financial services company that required secure software to protect sensitive customer financial data. The organization needed to ensure that its web application was protected against common vulnerabilities and followed secure coding best practices.



The primary objective was to identify software security vulnerabilities, mitigate risks, and ensure secure communication through encryption and proper dependency management.



Vulnerability Assessment and Secure Coding



During this project, I conducted a vulnerability assessment using OWASP Dependency-Check to identify known vulnerabilities in third-party dependencies. I reviewed the application’s configuration and ensured secure communication through HTTPS implementation.



Key security improvements included:



Implementing HTTPS using a self-signed certificate



Managing and updating dependencies using Maven



Running OWASP Dependency-Check to identify vulnerable libraries



Reviewing application configuration for secure settings



Secure coding is critical in financial systems because these applications handle sensitive information. Strong security practices help prevent data breaches, maintain regulatory compliance, and protect organizational reputation.



Challenges and Learning Experience



One challenging aspect of the vulnerability assessment was interpreting dependency-check results and understanding how third-party vulnerabilities impact application security. This process helped reinforce the importance of continuous monitoring and secure dependency management.



The most helpful part of the project was learning how automated tools assist in identifying risks that are not immediately visible in source code.



Security Layers and Future Improvements



To increase layers of security, I:



Enabled HTTPS for encrypted communication



Reviewed dependencies for known vulnerabilities



Ensured proper application configuration



In the future, I would expand vulnerability assessments using:



Static Application Security Testing (SAST)



Dynamic Application Security Testing (DAST)



Penetration testing tools



NIST and OWASP security frameworks



These tools help prioritize vulnerabilities based on severity and risk impact.



Ensuring Functionality and Security



After implementing security enhancements, I verified that:



The application compiled successfully



The REST endpoint returned expected responses



Dependency-check results reflected improved security posture



Testing ensured that security improvements did not introduce new functional issues.



Tools and Resources Used



Java



Spring Boot



Maven



OWASP Dependency-Check



HTTPS/SSL configuration



Secure coding best practices (OWASP Top 10 principles)



Portfolio Value



This project demonstrates my ability to:



Conduct vulnerability assessments



Apply secure coding practices



Use automated security tools



Implement HTTPS encryption



Document and communicate security findings clearly



This artifact reflects foundational skills in secure software development and application security, which are essential in cybersecurity and software engineering roles.

