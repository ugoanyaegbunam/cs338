## **Authors: Jeremiah, Ntense, Ugo**

## Scenario \#1: responsible reporting of security vulnerabilities

You have discovered a bug in the InstaToonz music-sharing app. This bug is a nasty one that would allow an attacker to read the contents of all the private InstaToonz direct messages for anyone who has ever posted a public InstaToonz message. This bug threatens the privacy of hundreds of millions of InstaToonz users.

You want to [report this bug](https://en.wikipedia.org/wiki/Responsible_disclosure) to InstaToonz, Inc. to protect their customers, but you know that the last time somebody reported a security bug to them privately, InstaToonz sued the bug-reporter in North Carolina and also called in the FBI, causing the person significant hassle and expense. The case was briefly a *cause célèbre* in the tech world, with calls for boycotts and state and Congressional action. Eventually, after a fair amount of sabre-rattling, InstaToonz dropped the suit. But at the same time, they released a statement articulating their belief that all security researchers (which InstaToonz always put inside scare quotes) are engaging in attempted thievery of trade secrets. After a brief investigation upon being first contacted by InstaToonz, the FBI declined to pursue the matter further. InstaToonz has refused all demands that they establish a [bug bounty program](https://en.wikipedia.org/wiki/Bug_bounty_program).

This scenario has an interesting legal twist if it occurs in the US. If you choose to analyze this scenario, take into account in your analysis two possible options:

* Suppose the bug involves the encryption and copy-protection of the music shared by InstaToonz users. You are not a lawyer, but you're concerned that your uncovering of this bug may put you in violation of [Section 1201 of the Digital Millennium Copyright Act.](https://en.wikipedia.org/wiki/Anti-circumvention)  
* Suppose the bug does not involve encryption or copy-protection.

1. **the main ethical question or questions faced by the main character ("you") in the scenario. This will certainly include "what should you do?", but there may be other interesting questions to consider.**  
   The main ethical questions getting faces are:  
   Whether or not to report the bug discovered to InstaToonz and risk getting sued by the company? This is based on InstaToonz past history as stated in the prompt where InstaToonz “sued the bug-reporter in North Carolina and also called in the FBI, causing the person significant hassle and expense”. Doing this questions whether the person should prioritize the safe of InstaToonz user’s privacy or your own legal risk.  
   Whether or not they are violating Section 1201 of the DMCA? This is because if the bug involves encryption and copy protection music, their is a potential risk of doing some malicious activities and violations which could lead to legal action being taken upon the bug reporter.  
     
     
2. **For each stakeholder (or category of stakeholders) in the scenario, identify the stakeholder's relevant rights.**

	**Users**:

- Data Privacy Rights  
  - Right to know who has their data, who it is shared with, and what it is being used for.  
  - Right to delete the data stored on the platform.  
  - Right to access their data.  
  - Right to untampered data.

	**InstaToonz**:

- DMCA (Anti-Circumvention)  
  - Allows companies to take legal actions against Circumvention  
  - Circumvention refers to the act of bypassing an encrypted system that has been put into place.  
- Coordinate Vulnerability Disclosure  
  - This is a widely accepted model that encourages users to report any bugs discovered directly to the company so they have ample time to repair the bug before publicly announcing it.

	

**Bug Finder:**

- DMCA (Circumvention)  
  - If a user bypasses placed encryption, it could be considered circumvention and therefore a felony.  
  - Requires caution, as even ethical hacking can result in illegal action  
3. List any information missing from the scenario that you would like to have to help you make better choices.  
   1. What type of security work are they doing on their end to where people like me don’t have to be the ones to come up with this stuff. If I was doing someone else’s job it would be one thing, and if the job already existed it would be another.  
   2. How the bug was discovered is super important. If I genuinely was bored and was just snooping around trying to break stuff and actually broke something, I would be worried about  [Section 1201 of the Digital Millennium Copyright Act](https://en.wikipedia.org/wiki/Anti-circumvention). However, if I was using the app regularly and out of nowhere noticed I had access to it, I wouldn’t need to worry about it.  
   3. How accessible is this bug, if it’s super niche then I need to worry about it a little less, versus it being super easy to find and do.  
   4. Whether the application has some sort of stamp of approval security wise, marking the security of the app.  
   5. On what grounds the FBI stopped the investigation and never punished the company  
4. Describe your possible actions, and discuss the likely consequences of those actions.  
   1. One option I have is to do nothing. I can live a quiet life and let rude people deal with the consequences of their rudeness. The consequence of that, though, is that someone a lot less nice than I am comes across the bug and starts selling messages.  
   2. I could report it because I want to be a good person and want the best for people. My consequences could be horrendous, though, and I might hate my life for a little bit. First, I’d have to deal with a bunch of hooligans from the company suing me. Then, if the stuff was encrypted, I would actually just cry because I can't win that case against section 1201\.  
   3. I could be diabolical and manipulate things with the information I have to profit and make my life better. The consequences would be an unclean conscience, and if I get caught I would actually be cooked. That can’t be legal.  
5. **Discuss whether the [ACM Code of Ethics and Professional Conduct](https://www.acm.org/about-acm/acm-code-of-ethics-and-professional-conduct) offers any relevant guidance.**

**Code 1.1 Contribute to society and to human well-being, acknowledging that all people are stakeholders in computing.**

The company InstaToonz should be more concerned about the well-being of its users rather than the possible legal violations committed by the individual who discovered the bug and may have possibly breached encryption.

**Code 1.2 Avoid harm.**

It would be ethical for InstaToonz to avoid enforcing legal harm on the user who discovered the bug, considering that the user wished to report the bug in good nature and accidentally stumbled upon the bug.

**Code 2.3 Know and respect existing rules pertaining to professional work.**

Though it would be ethical for the user to report the bug they found, due to rules and regulations regarding privacy and encryption, the user can still be legally convicted and held accountable for their actions.

**Code 2.9 Design and implement systems that are robust and usably secure.**

It should be one of InstaToonz's top priorities to ensure the reliability and security of their software. Any major risk discovered about the system should be willingly accepted and encouraged to share. 

6. Describe and justify your recommended action, as well as your answers to any other questions you presented in part A.

The most ethical course of action would be to report the bug due to the possibility of InstaToonz users' private information being maliciously used if accessed by an unethical party. However, in the case that InstaToonz doesn’t have a bug bounty program, the bug should be reported anonymously with the use of a certified third party or another company who is legally responsible for finding bugs and making it disclosed to the company. Doing this balances the ethical question to protect user privacy and security with your personal legal safety causing you to not expose yourself to unnecessary risks