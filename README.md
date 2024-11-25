# Software Security with SSL

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company that creates individualized financial plans for their clients. The range of plans that they offer include savings, retirement, investments, and insurance. The company is modernizing their operations, and want to update their software to include the most current and effective software security. They are currently using a RESTful web application programming interface (API).

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

Once I found what vulnerabilities that Artemis Financial had, using the Maven Dependency-Check plugin, I reviewed the dependency check report, and reviewed ways to upgrade or change any code that had a vulnerability and created a mitigation plan for the client. Secure code is vitally important. If a company is vulnerable, there could be an attack on their code, leading to data loss, viruses being uploaded, or even a complete failure of the system. A company's overall wellbeing is enhanced by software security, especially when handling sensitive data, such as Artemis Financial. If the company cannot be trusted to keep their clients information secure, the company will fail.

What part of the vulnerability assessment was challenging or helpful to you?

The biggest problem that I ran into with this course was in making sure that all of the software was correctly installed, such as Maven and the software needed to run a secure web application with HTTPS.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I used a Secure Socket Layer (SSL) to create a HTTPS site that I encoded with a has algorithm to encrypt the data. I would use Maven to run automated vulnerability checks on my code and identify and correct any deficiencies that it found.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I first used SPRING code that was already written to create the secure layers, and then used Maven to run a dependency check to find any vulnerabilities that were present. Afer refactoring the code, I ran another dependency check to find any new vulnerabilites. If there were new vulnerabilities, I would then refactor the code again and run the dependency check. This continues until there are no identified vulnerabilities that would affect the code.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Using imported coding tools such as the Spring platform, and the Maven dependency checks are of great benefit, because I don't have to write my own code for the same exact purpose. This saves much time and also ensures that I follow best practices by having uniform code. By also making sure that I follow object-oriented coding practices, and creating complete documentation, I make sure that others can read and understand my code.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show them the reports that I created that show that I know how to run vulnerability reports with the correct code, that I know how to refactor the code to eliminate the vulnerabilities, and that I know how to use the proper tools to create a secure environment for the code to run in.
