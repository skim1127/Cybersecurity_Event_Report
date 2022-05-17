# Cybersecurity_Event_Report
---

### <ins>2015 TalkTalk Data breach</ins>
Link to Article - [How an Outdated Database Led to a Data Breach](https://cyberstart.com/blog/how-an-outdated-database-led-to-a-data-breach-unpicking-the-talktalk-cyber-attack/)

1. <ins>What type of attack was this?</ins>
  ```
  This was a data breach, using a simple SQL injection cyber attack.
  ```
2. <ins>How was the vulnerability discovered?</ins>
  ```
  On October 15, 2015, the employees and users noticed that the network was much slower than usual. 
  As it turns out, TalkTalk took over an Italian telecommunications company called Tiscali in 2009, 
  who were using a very old way of code communicating with the database. The database itself 
  was not the problem, but rather the way the code communicated with it.
  ```
3. <ins>How were the attackers able to exploit the vulnerability?</ins>
  ```
  Investigations found that TalkTalk failed to update Tiscali's web pages, which made it easy for
  the attackers to interfere with the back-end database, stealing the data of all customer files.
  ```
4. <ins>Were there security measures that could have been taken in order to prevent this attack?</ins>
  ```
  They could have easily prevented this from happening by keeping their software up to date, and
  by hiring someone to change how the code communicates with the database.
  
  During the investigation, the ICO(Information Commissioner's Office) found out that 
  "the software was affected by a bug from many years ago, which allowed the attackers to bypass access 
  restrictions that were in place on the database. This bug had not been resolved, even though a patch 
  was readily available".
  
  The ICO fined TalkTalk £400k, but the overall cost of the attack was estimated to be much higher, 
  ranging between £30 million - 35 million.
  ```
---
### <ins>Ukraine Ransomware</ins>
Link to Article - [Tax Software Blamed for Cyber-Attack Spread](https://www.bbc.com/news/technology-40428967)

1. <ins>What type of attack was this?</ins>
  ```
  This was a ransomware spread, which involves an email aiming to make the recipient click on the file, 
  which is full of malware.
  ```
2. <ins>How was the vulnerability discovered?</ins>
  ```
  A Ukraininan tax-filing company, MEDoc, seemed to be the source of the infection, as many companies
  that were affected claim to have been using the MEDoc software.
  
  This cyber attack caused disruptions and infected companies in 64 different countries. The attacks 
  seemed to be mostly towards Ukraine, suggesting possible political motivations. According to investigations,
  80% of all attacks were in Ukraine.
  ```
3. <ins>How were the attackers able to exploit the vulnerability?</ins>
  ```
  the British malware expert Marcus Hutchins - credited with ending the WannaCry ransomware outbreak - 
  claim to have logs that reveal MEDoc as the source. Mr Hutchins said: 'It looks like the software's automatic 
  update system was compromised and used to download and run malware rather than updates for the software.'
  
  This is especially concerning, because the usual go-to method of preventing cyber attacks is to keep your
  software up-to-date. However, if the update is now the source for malware, it limits the users options because
  all they can do it trust in the software company.
  
  Once a PC is infected, the malware changes the operating system, locks the user out, then reboots the computer.
  Once the computer is rebooted, the malware demands the user payment for the decryption key if they want access to the computer.
  ```
4. <ins>Were there security measures that could have been taken in order to prevent this attack?</ins>
  ```
  The only way of preventing this type of cyber-attack seems to be to not click on files attached to emails in the
  first place. Once the malware is inside the computer, it uses a varirety of means to spread to other computers within
  the network.
  ```
