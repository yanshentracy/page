---
layout: post
title:  "SoundAuth: Secure zero-effort two-factor authentication based on audio signals"
link:  https://ieeexplore.ieee.org/abstract/document/8433202/
file:  
date:   2018-05-01 17:07:19
authors: M. Wang, W.-T. Zhu, <strong>S. Yan</strong>, and Q. Wang
pub: 6th IEEE Conference on Communications and Network Security (CNS'18)
page: pp. 1--9
categories: pub
---
<p><strong>Abstract:</strong> Two-factor authentication (2FA) popularly works by verifying 
something the user knows (a password) and something she possesses (a token, popularly 
instantiated with a smart phone). Conventional 2FA systems require extra interaction 
like typing a verification code, which is not very user-friendly. For improved user 
experience, recent work aims at zero-effort 2FA, in which a smart phone placed close 
to a computer (where the user enters her username/password into a browser to log into 
a server) automatically assists with the authentication. To prove her possession of the 
smart phone, the user needs to prove the phone is on the login spot, which reduces 
zero-effort 2FA to co-presence detection. In this paper, we propose SoundAuth, a secure 
zero-effort 2FA mechanism based on (two kinds of) ambient audio signals. SoundAuth looks 
for signs of proximity by having the browser and the smart phone compare both their 
surrounding sounds and certain unpredictable near-ultrasounds; if significant 
distinguishability is found, SoundAuth rejects the login request. For the ambient 
signals comparison, we regard it as a classification problem and employ a machine 
learning technique to analyze the audio signals. Experiments with real login attempts 
show that SoundAuth not only is comparable to existent schemes concerning utility, 
but also outperforms them in terms of resilience to attacks. SoundAuth can be easily 
deployed as it is readily supported by most smart phones and major browsers.</p>

<strong>Key Words:</strong>
<p>Zero-effort two-factor authentication; Ambient sound; Co-presence detection; Challenge-response protocol; Support vector machine; Time synchronization</p>