



### The CIA triad is the foundation of cybersecurity:

1. **Confidentiality ():**  **Keeping it secret, keeping it safe.** This means only authorized people can access your information. 

Example: Your login information (username and password) keeps your account details secret from unauthorized users. It's like having a secret code to access your bank

2. **Integrity (I):**  **Making sure it's accurate.** This ensures your data hasn't been changed or messed with.

Example: When you check your balance, you trust that the number reflects the actual money in your account. It's like knowing your bank hasn't been tampered with and the coins you counted are still there.

3. **Availability (A):**  **Having it there when you need it.** This means authorized users can access information whenever they need it. 

Example: You expect to be able to access your online bank account anytime you need to check your balance or make a transfer. It's like having easy access to your bank whenever you need to save or take out money.

Remember, cybersecurity is all about protecting your data: keeping it private (confidentiality), accurate (integrity), and accessible (availability).


### Achieving CIA - Best Practices

**Confidentiality: Keeping it Secret**

*  **Data Classification:**  Identify what data is sensitive and categorize it based on its confidentiality needs.  
*  **Encryption:** Encrypt sensitive data at rest and in transit to scramble it, making it unreadable without a decryption key.
*  **Access Controls:**  Implement strong access controls like user permissions and multi-factor authentication (MFA) to restrict access to authorized users only. 

**Integrity: Ensuring Accuracy**

*  **Data Validation:**  Put in place mechanisms to validate data accuracy during input, processing, and storage to prevent unauthorized modification.
*  **Logging and Monitoring:** Maintain detailed logs of system activity to identify and track any suspicious changes.
*  **Backups:** Regularly back up your data to ensure you have a clean copy in case of corruption or deletion.

**Availability: Keeping it Accessible**

*  **Redundancy:**  Build in redundancy measures like failover mechanisms and backups to ensure systems and data remain accessible even during outages.
*  **Patch Management:**  Regularly update systems and applications with the latest security patches to address vulnerabilities.
*  **Disaster Recovery (DR):** Develop and test a comprehensive Disaster Recovery (DR) plan to ensure quick recovery from security incidents.

**Best Practices for Overall CIA Triad Implementation**

* **Security Awareness Training:** Educate your employees about cybersecurity best practices to make them active participants in information security.
* **Regular Security Audits:** Conduct periodic security audits to identify and address any weaknesses in your security posture.
* **Risk Management:**  Proactively assess and manage security risks to your organization's data and systems.



* **Separation of Duties (SoD):** This principle prevents a single person from having complete control over a critical task. By dividing responsibilities, it reduces the risk of fraud or errors. (Supports Confidentiality & Integrity)

* **Mandatory Vacations:** Enforcing mandatory vacations helps prevent collusion and ensures someone else reviews tasks if a single person is consistently responsible. (Supports Confidentiality & Integrity)

* **Job Rotation:** Regularly rotating employees between different tasks reduces the opportunity for someone to exploit a specific weakness in their area of expertise. (Supports Confidentiality & Integrity)

* **Least Privilege:** This principle grants users the minimum level of access necessary to perform their jobs. By limiting access, you minimize the potential damage if someone's credentials are compromised. (Supports Confidentiality & Integrity)

* **Need-to-Know:**  Only authorized personnel with a legitimate business need should be granted access to specific information. This helps ensure sensitive data isn't exposed unnecessarily. (Supports Confidentiality)

* **Dual Control:** This principle requires two authorized individuals to approve or complete a critical task, further reducing the risk of errors or unauthorized actions. (Supports Integrity & Availability)

### DAD  Disclosure, Alteration and Destruction

DAD sounds pretty suspicious, right? It actually stands for Disclosure, Alteration, and Destruction, and it's the bad stuff people try to do with information security. Let's break it down in a simple way:

**Imagine you have a secret message for your friend.** You wouldn't want anyone else to read it, change it, or destroy it, right? That's what DAD is all about, but for important information like computer files or personal records.

* **Disclosure (Spreading secrets):** This is like someone finding your message and showing it to everyone! In the computer world, this means information getting leaked to unauthorized people. Hackers might steal it, or someone might accidentally send it to the wrong person.
* **Alteration (Tampering with the truth):** Imagine someone changing your message to something mean! In computers, this means someone messes with information, like changing grades in a school system or financial records at a bank. This can cause a lot of problems!
* **Destruction (Making things disappear):** This is like someone ripping up your message! In the computer world, this means information gets deleted or lost, like someone wiping clean all the customer data from a store's computer. This can be a huge mess to deal with.

**So, what's the opposite of DAD?** It's CIA, which stands for Confidentiality, Integrity, and Availability. This is what we want for information security:

* **Confidentiality (Keeping things secret):** Only the people who are supposed to see your message can see it.
* **Integrity (Making sure things are accurate):** Your message stays the same, no changes!
* **Availability (Being able to access things):** You can always find your message when you need it.

Basically, DAD is bad because it messes with information security, and CIA is good because it keeps things safe and sound!




### IAAA (Identification, Authentication, Authorization, and Accountability)
Imagine you're entering a school building:

1. **Identification (Who are you?)** - You show your ID card at the front desk. This identifies you as a student, teacher, visitor etc.
2. **Authentication (Is your ID valid?)** - The security guard checks your ID to make sure it's real and belongs to you.
3. **Authorization (What are you allowed to do?)** - Based on your ID (student/teacher/visitor), you are granted access to certain areas of the school.
4. **Accountability (We keep track of who enters)** - Security cameras are recording activity throughout the school for safety purposes. This way, they know who was in the building at a certain time.

**Accountability is basically making sure someone is responsible for their actions.** In the school example, if there's damage in the computer lab, they can check the cameras to see who was there. 

IAAA (Identification, Authentication, Authorization, and Accountability) works in a similar way for computer systems and online accounts. It ensures that only authorized people can access the system and that they are held responsible for what they do while logged in.