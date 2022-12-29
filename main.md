Proof of Concept / description

A Stored Cross-Site Scripting vulnerability exists in the web application. A user can use Base Tag Hijacking in order to redirect relative Javascript imports to a malicious attacker-controlled server. The attacker can host a file containing arbitrary Javascript code.

Firstly, let's create an account and login.

![](1.png)

![](2.png)

![](3.png)

I will, then, setup a Python Simple HTTP Server in order to host the external Javascript files. I can, then, inject a Base tag and redirect it to my machine in order to achieve Base Tag Hijacking so that it will execute said attacker-controlled Javascript files.

![](5.png)

![](4.png)

