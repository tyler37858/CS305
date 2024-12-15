# CS305
Project 2 submission 

1.Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Specializing on financial planning services including savings, retirement, investments, and insurance, the customer, Artemis Financial, is a consulting firm. Their need for a solution guaranteed the safe client data transmission and verification. In particular, they aimed to enable HTTPS for their online application to improve data integrity and communication security and apply a checksum verification stage.

 2.What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  I successfully found and fixed vulnerabilities in antiquated dependencies, then upgraded to safe versions of libraries including Jackson Databind and Hibernate Validator. Protection of customer data from risks including data breaches and illegal access depends on safe coding. Excellent software security guarantees industry compliance, lowers risks, and helps a company maintain its brand.

3. Which part of the vulnerability assessment was challenging or helpful to you?

  Identifying outdated dependencies and understanding their vulnerabilities was challenging yet insightful. Using OWASP Dependency-Check was helpful in automating the detection of security flaws and prioritizing fixes. This experience reinforced the importance of using tools to streamline vulnerability assessments.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  HTTPS enabled via a self-signed SSL certificate and SHA-256 for checksum verification added layers of security. To find and reduce vulnerabilities, I would keep utilizing tools like OWASP Dependency-Check and apply other testing methods such penetration testing and dynamic application security testing (DAST) going forward.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

   Functional testing of the checksum endpoint and dependency analysis helped to guarantee no vulnerabilities were added by the code. Following restructuring, the OWASP Dependency-Check was repeated to ensure that all dependencies stayed safe; the application logs were then checked to confirm appropriate operation.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

   Finding and correcting vulnerabilities proved greatly assisted by tools like Maven and OWASP Dependency-Check. The main points were on safe coding techniques including turning on HTTPS and using strong cryptographic hashings. These tools and processes will help to guarantee the dependability and security of next initiatives.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

   I would highlight my ability to spot and fix software flaws, use secure coding techniques, guarantee compliance to modern security guidelines, and so forth. I would stress the effective combination of HTTPS and cryptographic hash as well as my usage of automated tools like OWASP Dependency-Check to improve the general security posture of the product.
