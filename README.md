# Task-2-Analyze-a-Phishing-Email
CYBER SECURITY INTERNSHIP

Sample email obtained 

Google password change mail

<img width="738" height="478" alt="image" src="https://github.com/user-attachments/assets/9c153776-cdbf-4384-8228-2ffc2ac82b05" />

1) Mail id 0 used instead of o in google and profile picture has no official google logo
   <img width="739" height="479" alt="image" src="https://github.com/user-attachments/assets/4d664d01-7001-49e5-83ab-03cf5e5ba2e6" />

2) No personalised greeting just "Hi", big companies usually address by name when sending mails
   <img width="738" height="478" alt="image" src="https://github.com/user-attachments/assets/0f498eaf-a98b-4df4-8afc-fc5ece2bdd24" />

3) Creating a sense of urgency by using "immediately" and scaring the recepiant
   <img width="738" height="478" alt="image" src="https://github.com/user-attachments/assets/43af31ad-8731-4c3a-8f87-da94509d8f20" />

4) Hovering on the button shows a link that directs you to a random domain ml-security.org
   <img width="1347" height="564" alt="image" src="https://github.com/user-attachments/assets/311fb5f2-85b7-49a7-b2c1-62e1bde74832" />

   Header analysis cannot be done on a sample but if a suspicious email is sent to our mail id, header analyzers can help in making complex header information plain text so that it is easy to find out issues in the mail.

**Questions**

1. What is phishing?
      
Phishing is a cyberattack technique where attackers impersonate legitimate entities (like banks or companies) to trick users into revealing sensitive
information such as passwords, credit card details, or login credentials. It often occurs through emails, fake websites, or messages.

2. How to identify a phishing email?

Suspicious sender address (slight variations of legitimate domains).
Urgent or threatening language.
Unexpected attachments or links.
Poor grammar or spelling errors.
Mismatched URLs (hover over links to check actual destination).
Requests for personal or financial information.

3. What is email spoofing?
      
Email spoofing is when attackers forge the sender’s email address to make it look like the email is coming from a trusted source.
Used to bypass trust and increase chances of phishing success.

4. Why are phishing emails dangerous?

Can steal confidential data (passwords, banking info, etc.).
Can install malware or ransomware when attachments or links are opened.
Lead to financial loss or identity theft.
Enable unauthorized access to corporate networks or accounts.

5. How can you verify the sender’s authenticity?

Check the full sender email address (not just the display name).
Inspect the email header for the real source domain.
Hover over links to verify they lead to legitimate sites.
Contact the organization directly through official channels.
Use DKIM, SPF, and DMARC record checks for domain validation.

6. What tools can analyze email headers?

Google Admin Toolbox Messageheader
MXToolbox Email Header Analyzer
Microsoft Message Header Analyzer (Outlook add-in)
Mailheader.org
Wireshark (for deeper packet analysis).

7. What actions should be taken on suspected phishing emails?

Do not click on any links or attachments.
Report the email to your IT/security team or email provider.
Mark as spam or phishing in your email client.
Block the sender’s address/domain.
Delete the email after reporting.
If clicked accidentally, change passwords immediately and run antivirus scans.

8. How do attackers use social engineering in phishing?

Attackers exploit human emotions like fear, curiosity, urgency, or trust.
They pose as trusted figures (boss, bank, service provider).
They use personalized messages (from stolen data or OSINT) to seem legitimate.
They manipulate victims into clicking links, downloading files, or giving up information.
