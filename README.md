Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Client: Artemis Financial, a consulting firm that creates customized financial strategies for customers.
Software Requirements: Artemis Financial want to update their business practices and provide safe connections while exchanging financial and client data. They asked for:
File verification: Including a checksum phase to ensure data integrity in the web application.
Encrypting communications by switching from HTTP to HTTPS.
Vulnerability Analysis and the Significance of Secure Coding

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I found vulnerabilities in the client's software related to the lack of data verification and secure communication protocols. To address these issues, I:
Recommended and implemented an appropriate encryption algorithm cipher (e.g., AES-256). Secure coding is crucial to build trust and protect sensitive data. It prevents unauthorized access, data breaches, and reputational damage. It also promotes user confidence and fosters a secure environment for financial transactions.

What part of the vulnerability assessment was challenging or helpful to you?
Challenging:
Choosing the optimal encryption algorithm based on factors like performance, security level, and key management.
Integrating the chosen algorithm seamlessly into the existing codebase without compromising functionality.
Helpful:
The provided Vulnerability Assessment Process Flow Diagram offered a structured approach to identify and address vulnerabilities.
Static code analysis tools like OWASP Dependency-Check helped detect potential vulnerabilities early in the development process.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Increased Layers of Security:
Implemented checksum verification for data integrity.
Converted HTTP to HTTPS for secure communication.
Used industry-standard secure coding practices for input validation, error handling, and access control.
Future Assessment:
Employ a combination of static and dynamic code analysis tools.
Stay updated on the latest security threats and vulnerabilities.
Utilize penetration testing to simulate real-world attacks and identify weaknesses.
Ensuring Functionality and Security

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Functionality:
Refactored code without errors through careful planning, testing, and iteration.
Used screenshots of the refactored code running successfully to demonstrate functionality.
Security:
Performed static code analysis using OWASP Dependency-Check to identify potential vulnerabilities introduced during refactoring.
Manually reviewed the code for syntactical, logical, and security vulnerabilities.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Encryption algorithms: AES-256, RSA
Static code analysis tools: OWASP Dependency-Check
Coding practices: Input validation, error handling, access control, secure libraries
Testing tools: JUnit

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
Project report: Demonstrates understanding of secure coding principles and vulnerability assessment.
Refactored code: Showcases ability to implement secure coding practices and enhance security without sacrificing functionality.
Screenshots: Visually illustrate successful implementation and testing of secure communication mechanisms.
