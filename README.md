Project One Overview

Artemis Financial is a consulting company that develops individualized financial plans including savings, retirement, investments, and insurance strategies. The company wanted to modernize its RESTful API and strengthen its overall software security posture. The main issue was identifying and mitigating security vulnerabilities in its web based application. The goal was to perform a full vulnerability assessment, identify weaknesses in the code base and dependencies, and propose a mitigation plan to protect the organization from external threats.

What I did well

I performed a structured vulnerability assessment using both manual code review and automated static analysis. During the manual review, I carefully inspected the source code to identify insecure practices such as improper input handling, insecure configurations, and weak cryptographic usage. I documented each finding clearly, including file locations and explanations. Using OWASP Dependency Check through Maven, I identified known vulnerabilities in third party libraries. I analyzed the CVE entries, reviewed severity scores, and documented recommended fixes.

Coding securely is critical because financial systems handle sensitive data. If security is weak, customer information can be exposed, legal consequences can occur, and trust can be permanently damaged. Strong software security protects data confidentiality, maintains system integrity, and ensures availability of services. For a financial company, that directly affects reputation and long term survival.

The most difficult and helpful parts

The most challenging part was interpreting static analysis results and understanding which vulnerabilities were actually relevant to the application. Not every warning has the same level of risk. Learning to prioritize based on severity and exploitability was important. The most helpful part was running dependency analysis. It clearly showed how insecure third party libraries can introduce risk even when your own code looks clean. That reinforced the importance of monitoring open source dependencies continuously.

Increasing layers of security

I increased layers of security by reviewing and enforcing secure communication practices such as HTTPS, identifying outdated dependencies and recommending updates, documenting mitigation strategies for each vulnerability, and by applying secure coding principles during review.

In the future, I would use OWASP Dependency Check, static code analysis tools, penetration testing tools, OWASP Top 10 guidelines as a reference, and continuous integration pipelines with automated security scans. I believe that security should not be a one time task. It should be integrated into development workflows.

Ensuring functionality and security

After reviewing and refactoring the code, I ensured functionality by confirming that the application still compiled and executed without runtime errors. I re ran static testing after changes to verify that no new vulnerabilities were introduced. Security testing must be iterative. Every modification to code can introduce new risk. Re testing after refactoring is necessary to confirm improvements did not create additional weaknesses.

Methods used

I used Maven build management, OWASP Dependency Check plugin, manual code review, vulnerability documentation practices, and secure software development lifecycle concepts. These tools and practices will be useful in future projects involving web applications and secure API development.

What I'll show future employers

From this assignment, I would show: A completed vulnerability assessment report, evidence of static analysis integration into a Maven project, documented mitigation planning, and structured security evaluation process.

This project demonstrates that I can evaluate real software systems, identify security risks, and propose practical mitigation strategies. It shows understanding of secure development practices and the ability to apply industry tools to assess and improve software security.
