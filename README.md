# CS-305

Client Summary
- The client, Artemis Financial, is a company that offers financial consulting services and is looking to strengthen the security of its online platform, prioritizing the safety of client data and financial information. As a financial services provider, Artemis Financial stores significant amounts of personally identifiable information (PII), including client names, social security numbers, financial account details, and sensitive transaction records. Given the high-value nature of this data and the severe consequences of a potential breach, the company has prioritized the need for  security guidance to protect against severe cyber threats.

Security Vulnerabilities and Secure Coding
- Upon reviewing the client's code base and current structure, I did well in identifying the vulnerabilities, assessing the current process, and building a plan on how to properly secure the application using industry standard practices. It is important to code securely because attackers will take advantage of a system with weak security integrity and have proven doing so in the past. Staying up to date with common errors, similar to how we utilized the dependency checks to check for new vulnerabilities, ensures that not only user data is secure but company data is as well. This also ensures companies are remaining in compliance with laws set to protect those from these types of cyber attacks.

Challenges
- While completing this vulnerability assessment, I ran into a few problems generating certificates and running the dependency checks. These problems were caused by incorrect system configurations that I was able to solve with help from Stack Overflow, as the errors I received had been common and easily fixable. Once remedied, I was able to run the appropriate tests and conduct proper manual review. The overall process was helpful in strengthening my problem-solving skills and gave great insight into proper security protocols and ideas for future projects.

Layers of Security
- When adding layers of security to the program, I approached it by having each layer built upon the previous one. First, I generated a digital certificate to enable HTTPS encryption, establishing secure communication. Next, I implemented a hash algorithm to protect sensitive data from exposure. I then configured the application to use the HTTPS protocol, leveraging the certificate to encrypt data in transit. In the future, I would likely continue utilizing the vulnerability assessment process flow diagram to create a plan to mitigate.
 
Functional Code
- To ensure that my code was functional and secure, I had to implement both dynamic and static testing. I had to conduct a manual review of the code base prior to running the program to identify what aspects or important security functions or properties were missing or inconsistent. I then had to run dependency checks to identify known vulnerabilities in the dependent libraries and ensure all components were up to date with the latest security patches. Finally, I had to run the program and ensure it built successfully and produced the expected output, confirming that all security implementations functioned correctly without effecting existing functionality.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
- The OWASP checks were by far the most interesting and useful tool I plan to use for future projects and assignments. When examining the before and after, it's an effective way to get an idea of why your program isn't functioning properly or running as securely as you may believe, and it also includes a detailed explanation as to why.

Future employers
- For this assignment, I think showing the finalized report with detailed explanations and screenshots as to what was completed, why it was completed, and its importance would be a great way to demonstrate skills and problem-solving abilities. Including visual evidence of the vulnerabilities identified and the solutions implemented provides concrete proof of my ability to assess, analyze, and mitigate security issues in real world applications.
