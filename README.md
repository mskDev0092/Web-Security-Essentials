## Web Security Essentials

> Web security essentials refer to the fundamental principles and practices that should be followed in order to ensure the security of web applications. This includes such things as proper authentication and authorization, input validation, output encoding, session management, error handling, and more. Following these security essentials can help to protect web applications from common security vulnerabilities, such as cross-site scripting (XSS) and SQL injection attacks. Additionally, following these security essentials can help to ensure that data is encrypted and secure, and that the integrity of the data is maintained.


| Table of Contents  |
| --- |
|1. HTTPS matters |
|2. OWASP Web Application Security Testing Checklist  | 
|3. OWASP Top 10 Security Risks & Vulnerabilities | 
|4. OWASP Cheat Sheet |
|5. Content Security Policy (CSP) |
|6. Cross-Origin Resource Sharing (CORS) |
|7. What is TLS? |
|8. What is bcrypt? |
|9. Server Security |

# 1. HTTPS matters

> HTTPS helps to ensure that communications between a website and a user's browser are secure and not tampered with by unauthorized third parties. It helps to protect users from malicious attacks, such as man-in-the-middle attacks, where an attacker can intercept and modify data being sent between the two parties. HTTPS also helps to ensure that the website is the legitimate one and not an imposter site. Furthermore, HTTPS helps to ensure that data is encrypted, making it difficult for attackers to access and read the data. Finally, HTTPS also helps to ensure the integrity of the data being sent, as the data is verified to be unaltered when it reaches its destination.

- Learn More URL: [https://web.dev/why-https-matters/](https://web.dev/why-https-matters/)

# 2. OWASP Web Application Security Testing Checklist

> The OWASP Web Application Security Testing Checklist is a comprehensive list of tests that should be performed when testing the security of a web application. The checklist covers areas such as authentication, authorization, input validation, output encoding, session management, error handling, and more. This list can be used to ensure that all areas of a web application are tested and that no security weaknesses are overlooked. Additionally, the checklist can help to guide security testers in their security testing efforts, ensuring that all relevant areas are tested and that no tests are missed.

- Learn More URL: [https://github.com/0xRadi/OWASP-Web-Checklist](https://github.com/0xRadi/OWASP-Web-Checklist)

# 3. OWASP Top 10 Security Risks & Vulnerabilities

> The OWASP Top 10 is a list of the ten most common and critical web application security risks. It is designed to help developers identify and address security vulnerabilities in their applications. The list is updated regularly These risks are ranked according to the frequency of discovered security defects, the severity of the uncovered vulnerabilities, and the magnitude of their potential impact.

- List 2023

- [ ] 1. Broken Access Control: 

> This refers to any system that fails to properly restrict access to resources or data, allowing unauthorized users to gain access.

- [ ] 2. Cryptographic Failures: 

> This occurs when cryptographic security controls fail to protect data and can result in unauthorized access or modification of data.

- [ ] 3. Injection: 

> This occurs when malicious user-supplied data is inserted into an application, allowing attackers to execute malicious code or access confidential data.

- [ ] 4. Insecure Design: 

> This refers to insecure software design practices which can lead to vulnerabilities, such as the lack of input validation, lack of authentication, or weak authorization controls.

- [ ] 5. Security Misconfiguration: 

> This includes any misconfigured security settings or features, such as unpatched systems, disabled security features, or insecure default configurations.

- [ ] 6. Vulnerable and Outdated Components: 

> This refers to the use of vulnerable and outdated libraries, frameworks, or other components, which can lead to security issues if not updated.

- [ ] 7. Insufficient Logging and Monitoring: 

> This refers to a lack of logging and monitoring capabilities, which can make it difficult to detect and investigate security incidents.

- [ ] 8. Cross-Site Scripting (XSS): 

> This is a type of attack which injects malicious code into a web application, allowing attackers to steal data or gain control of the application.

- [ ] 9. Broken Authentication: 

> This refers to the failure of authentication mechanisms, such as passwords or tokens, which can result in unauthorized access to sensitive data or systems.

- [ ] 10. Application Denial of Service: 

> This is a type of attack which renders an application or service unavailable by flooding it with malicious requests or traffic.



- Learn More URL: [https://sucuri.net/guides/owasp-top-10-security-vulnerabilities-2020/](https://sucuri.net/guides/owasp-top-10-security-vulnerabilities-2020/)

# 4. OWASP Cheat Sheet

> The OWASP Cheat Sheet Series is a collection of documents which aim to provide a concise collection of security best practices for web applications. The documents provide a guideline to help developers avoid common security issues when creating web applications. The cheat sheets cover topics such as authentication, input validation, session management, error handling, and more. Additionally, the cheat sheets provide links to more in-depth resources and tutorials to help developers better understand the subject matter.

- Learn More URL: [https://cheatsheetseries.owasp.org/cheatsheets/AJAX_Security_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/AJAX_Security_Cheat_Sheet.html)

# 5. Content Security Policy (CSP)

> Content Security Policy (CSP) is a security mechanism that helps to protect web applications from cross-site scripting (XSS), data injection attacks, and other malicious activities. It works by instructing web browsers on what type of content is allowed to be loaded and executed on a page, and helps to prevent malicious code from being executed. CSP can be enforced by adding a header to an HTTP response, or by adding a meta tag to an HTML page. CSP can also be used to restrict the use of certain APIs such as eval(), making it more difficult for attackers to execute malicious code.

- Learn More URL: [https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)

# 6. Cross-Origin Resource Sharing (CORS) 

> Cross-Origin Resource Sharing (CORS) is a mechanism that allows web applications to make requests from different domains . It is a set of rules that define which resources a web application can access from a different domain. CORS works by adding a special response header that allows the web application to specify which other domains are allowed to make requests. When a web application makes a request to a server, the server will check the request headers to determine if the request originates from an allowed domain. If the origin is not an allowed domain, the server will reject the request. CORS is an important security feature that prevents malicious actors from making requests to a web application from outside of the intended domain.

-  Learn More URL: []()
 
# 7. What is TLS?
 
>

- Learn More URL: []()

# 8. What is bcrypt?

>

- Learn More URL: []()

# 9. Server Security

>

- Learn More URL: []()





