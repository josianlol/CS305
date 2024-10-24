# CS305
Software Security

Client and Software Requirements

Artemis Financial, a financial services company, sought to enhance the security of their software to protect sensitive data, such as client financial records and personal information. Their primary concern was ensuring that their web application, which facilitated various financial transactions, was secure from common vulnerabilities and capable of handling secure communication over HTTPS.

The specific issue Artemis Financial wanted to address was the lack of a secure SSL configuration within their Spring Boot web application. They required the implementation of a secure connection (HTTPS) using SSL certificates and a comprehensive assessment of security vulnerabilities within their project to mitigate any risks.

What Went Well When Addressing Software Security Vulnerabilities

In identifying and addressing Artemis Financial’s security vulnerabilities, I was meticulous in following secure coding practices, particularly in securing sensitive data and ensuring encrypted communications via SSL. The process of creating and integrating a keystore, generating SSL certificates, and configuring Spring Boot to use HTTPS went smoothly. I also utilized the OWASP Dependency Check tool to identify vulnerabilities in third-party libraries.

Importance of Secure Coding

Secure coding is crucial because it prevents potential breaches that could lead to the loss or theft of sensitive data, financial fraud, or damage to a company’s reputation. Implementing software security practices adds value to a company’s overall well-being by safeguarding client data, ensuring regulatory compliance, and fostering trust among users. It also reduces the risk of costly incidents like data breaches and downtime.

Challenging and Helpful Aspects of the Vulnerability Assessment

One of the challenging aspects of the vulnerability assessment was resolving issues related to setting up the SSL keystore and ensuring proper SSL configuration. This involved understanding the intricacies of certificate management and ensuring that the application was configured to trust the keystore properly.

A helpful part of the process was using OWASP’s Dependency Check, which provided a clear and systematic way to identify vulnerabilities in third-party libraries. It streamlined the process of locating potential security issues that could arise from using outdated or insecure libraries.

Increasing Layers of Security

I increased layers of security by implementing SSL certificates to encrypt communication, which ensured the secure transmission of sensitive data. Additionally, I enforced strong password management practices for the keystore, applied secure coding practices, and performed thorough testing to ensure no vulnerabilities were introduced during refactoring.

In the future, to assess vulnerabilities, I would continue using tools like OWASP Dependency Check for third-party libraries, static code analysis tools like SonarQube, and comprehensive penetration testing tools to assess the system’s security. To decide on mitigation techniques, I would follow a risk-based approach, prioritizing vulnerabilities with the highest potential impact.

Ensuring Functionality and Security After Refactoring

After refactoring the code, I performed several tests to ensure that the application remained functional and secure. This included running the application with the newly configured SSL certificates and ensuring it was reachable via HTTPS. I also re-ran the OWASP Dependency Check to confirm that no new vulnerabilities had been introduced.

Helpful Resources, Tools, and Practices

The tools and practices that proved most helpful in this project included:

	•	OWASP Dependency Check for identifying vulnerabilities in third-party libraries.
	•	Keytool for managing SSL certificates and keystores.
	•	Maven for managing dependencies and building the Spring Boot application.
	•	Spring Boot’s built-in security features for configuring SSL/HTTPS and ensuring secure web application development.

These tools and practices will be invaluable in future projects, especially in secure application development, vulnerability assessments, and dependency management.

Demonstrating Skills to Future Employers

From this assignment, I could show future employers my ability to:

	•	Secure a web application by implementing SSL/TLS encryption and performing vulnerability assessments.
	•	Refactor code while maintaining security and functionality.
	•	Use industry-standard tools to identify and mitigate security risks.
	•	Develop secure software solutions that protect sensitive data and ensure compliance with security standards.

This demonstrates my understanding of secure coding practices, my experience with common security tools, and my ability to improve the security posture of a web application.
