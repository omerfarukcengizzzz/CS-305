# CS-305


## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a company that provides financial services and needs secure and reliable software to protect sensitive client data. My task was to address software vulnerabilities in their application and ensure it met industry security standards. The main issue I faced was related to outdated dependencies and weak cryptographic practices, which could potentially expose the system to threats.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I was able to find and address the security vulnerabilities in Artemis Financial's application effectively. Using tools like OWASP Dependency Check, I analyzed and mitigated risks by either suppressing false positives or resolving real issues. It’s important to code securely because it protects the company’s reputation and builds trust with clients. Secure coding also prevents costly breaches, which are critical for a company’s overall success.

## Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging part of the vulnerability assessment was understanding the dependencies and ensuring the suppressed vulnerabilities were valid. This required careful analysis and justification for each suppressed item. However, going through this process helped me learn a lot about how vulnerabilities are assessed and mitigated in real world scenarios.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
To improve security, I added several layers of protection. I enabled HTTPS communication by implementing SSL/TLS, upgraded cryptographic algorithms to SHA-256, and addressed vulnerabilities in the project dependencies. Moving forward, I plan to use tools like OWASP Dependency Check and static code analysis tools regularly to keep systems secure.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After making the changes, I ran several tests to make sure the code was both functional and secure. I used the dependency check tool again to confirm that no new vulnerabilities had been introduced. I also manually reviewed the code and verified that the application performed as expected, ensuring that it met all security requirements.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I relied on OWASP Dependency Check and Maven for analyzing and managing dependencies. These tools were incredibly helpful in identifying vulnerabilities and ensuring that the project adhered to secure coding practices. I also applied secure coding principles throughout the project, which will be valuable for future assignments and tasks.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
If an employer wanted to see examples of my work, I would show them the refactored code and the vulnerability assessment report I created. These documents demonstrate my ability to identify and resolve security risks, implement secure coding practices, and ensure that applications are both functional and safe. It’s a great way to showcase my skills and experience in building secure software.
