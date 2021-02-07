# Vianet - Real Case Story

###### (**10 minutes read**, if you don't understand just keep on reading it you'll understand it for sure)

## Introduction

_V_ ianet faced the [biggest data breach in the history of Nepal](https://ictframe.com/vianet-falls-victim-to-data-breach-customer-data-compromised/). Exposing more than 1,76,000 customer's private information which contained their customer id, name, address, phone number, email address which had a massive impact on the customers rather than the company itself. I AM SORRY for the mess, my family/relatives too had an equal impact from the incident. And, I feel that people are curious about the breach. When, Why, and How did the breach occur? What was the motive of it? Why Vianet? Why Narpichas? Who is Bramhapichas? Do I know SATAN? Am I a full-time bad actor? etc... Which I will cover in the following article.

## Why

Being just a regular [infosec](https://en.wikipedia.org/wiki/Information_security) guy. We go through several [security vulnerabilities](https://en.wikipedia.org/wiki/Vulnerability_(computing)) (a way to hack into something) We don't even have to actively sit checking for vulnerabilities, we can simply sense it from far away. And, one of the ways of making the mind happy is helping someone. I love to help people. So, whenever I go through a known security vulnerability, I report it through anonymous means since I don't want to get into any trouble. But some worst creatures on Earth. I am talking about those lame Nepali Developers who even agree to work under-paid snatching a good and experienced developer's chance to work on a project. They don't even know a pinch full of security. And, act as if they are the God of application development, sad little newbies. Since they don't have any idea about it. They don't care about the reports. I sometimes feel that they don't understand the reports in the first place.

And, other developers simply ignore it because they're busy on other projects worth way more than the one they received the vulnerability report of. Also in most cases, they just don't care at all and, give up an excuse like: "who might sit hacking this little application." Dear developers, if someone can [Remote Code Execution (RCE)](https://en.wikipedia.org/wiki/Arbitrary_code_execution) in your application they can use up your resources to perform other malicious activity. So, do care about it. The above RCE thing was just an example, leaving even a single security vulnerability can cause massive and unexpected damage.

I am not a full-time bad actor in the following field, I am not even a bad actor to be even more exact. I've been reporting developers, by not expecting any rewards in any form. Forget silently [patching](https://en.wikipedia.org/wiki/Patch_(computing)) the security vulnerability. Forget a Thank You. One of my friends got an F You in return (I am talking about Mr. Khadka who spends his free time reporting vulnerabilities.)

Their behavior isn't good doesn't mean, I'll act the same to them. I thought they might not be well aware of the consequences if a vulnerability is left unpatched. Therefore, I decided to show up consequences by acting as if I am a full-time malicious actor. Another thing to be noted: I didn't do it to earn even a single penny, and none provided me one. I do not work for making cash through malicious actives, and will never work too. It's just hard to digest the currency made through bad means, as per my grandpa. And, another thing to note would be if I didn't breach it. Some other crazy threat might breach it or could also sell it without any notice to anyone.

I do not say, what I did was good. But, I would like to state that the intention behind the whole disaster wasn't malicious or to trouble anyone. I was a kid (16 years old) when I breached it. I am very sorry to the entire Vianet customers. And, to the Vianet too for the unexpected mess. But, people in Nepal should also be aware that their data isn't secure. Your several private information could be accessed very easily, through several channels. And, due to irresponsible developers who do not care about anything at all.

## Incident

Reports do get ignored, not everywhere though so I wanted to write a few [scripts](https://en.wikipedia.org/wiki/Scripting_language) for some ease in [bug bounty programs](https://en.wikipedia.org/wiki/Bug_bounty_program) which would let me identify [security vulnerability](https://en.wikipedia.org/wiki/Vulnerability_(computing)) or [bugs](https://en.wikipedia.org/wiki/Software_bug) like [SQL injection](https://en.wikipedia.org/wiki/SQL_injection), [IDOR](https://en.wikipedia.org/wiki/Insecure_direct_object_reference), etc. without even looking for it. Used case? I would just browse through the Internet and it would automatically try the [payloads](https://en.wikipedia.org/wiki/Payload_(computing)) and predict if the security vulnerability exists based on the response of it also thanks a lot to [queuing](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)), [logging](https://en.wikipedia.org/wiki/Log_file) web requests and responses through any mean like a web browser, network-wide [proxy](https://en.wikipedia.org/wiki/Proxy_server), [SSL/TLS](SSL/TLS) [unpinned](https://serializethoughts.com/2016/08/18/bypassing-ssl-pinning-in-android-applications) android through a proxy and [regex](https://en.wikipedia.org/wiki/Regular_expression) for ease in the prediction of the existence of the vulnerability. So, I started to work for it then later I was testing it on randomly proxied traffic. Which contained one of [Vianet](https://www.vianet.com.np/)'s [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) [Web](https://en.wikipedia.org/wiki/Web_API) [API](https://en.wikipedia.org/wiki/API) requests vulnerable to IDOR.

##### In plain English, it just means that my code was able to hack into Vianet, through a bug leaking all of the customer details. Yes, I did not manually do it my code did it for me. I now had something really powerful. But, as I've stated no one cares about it. So, I decided to just save it as it is on my device and let it be as it is until I ever need it.

Then after a long time, I saw [Foodmandu's breach](https://ictframe.com/foodmandu-a-kathmandu-based-food-delivery-service-has-been-hacked/). I was literally like, "Wait! Does that thing exist in Nepal?" Coool!! So, reporting doesn't work for the lame developers. I thought those worst creatures on Earth aren't aware of the consequences but I didn't target Vianet. It was just that I already had the [exploit](https://en.wikipedia.org/wiki/Exploit_(computer_security)) and it was HUGE! 

Since I already knew the security vulnerability. I just had to write another script to dump the details of the entire Vianet's customer details (more than 1,76,000) For it, I used [100 threads](https://en.wikipedia.org/wiki/Multithreading_(computer_architecture)) while my [IP Address](https://en.wikipedia.org/wiki/IP_address) was changed every 4 seconds. All thanks to [The Onion Router (Tor)](https://en.wikipedia.org/wiki/Tor_(anonymity_network)) for the random IP address changes. It took around 10-20 minutes to dump the entire data.

Now, the original dump was on [JSON](https://en.wikipedia.org/wiki/JSON) so I converted it into [CSV](https://en.wikipedia.org/wiki/Comma-separated_values). Since I didn't want it to be in the wrong hands, therefore I uploaded it to an expiring paste-bin then created an account, and I choose the name Narpichas because I initially wanted to use the name Bramhapichas which means a student killed before s/he is expected to die. (विद्यार्थीको अकालमा मृत्यु) Later I thought the name was too long enough so, used Narpichas which meant devil with a human body and Narpichas sounds more classic and cooler than Bramhapichas. Later with the same account, I tweeted the following:
<img src="/static/img/tweet_0.jpg">


I didn't see any activities so I decided to mention Vianet. But didn't find any Twitter account that looked like the original Vianet's account. So, I tweeted this:

<img src="/static/img/tweet_1.jpg">

Again, after an hour without any activity I decided to make fun of [Mr. Mugger](https://twitter.com/mr_mugger) through a poem that I'd simply written to make things look serious while making fun out of him via the following tweet:

<img src="/static/img/tweet_2.jpg">

The above tweet didn't mean anything much, since Nepalese people just believe what they've seen without thinking for a moment. I just managed to be known as the most [sinful hacker of all time](https://www.nepalitimes.com/latest/thank-you-satan/). Just calm down for a while, there are way more serious threats in the nation. I just did it, because I thought it might give a taste to big companies of Nepal of not caring about the vulnerability report. And mentioning it again, that I did not target Vianet, it's just that the customer base of Vianet was huge and I'd found the vulnerability. The thing to note: your so-called SATAN (whom I don't know personally) was just grabbing attention by just displaying old known and most of the fixed vulnerabilities. **HE ISN'T A REBEL, HE WAS JUST TRYING TO ACT LIKE ONE**. Even his name looks like he is doing his best to grab some attention LMAO. And, dear Sakar Pudasaini and Prayush Bijukche, **Grey Hats ALSO DO CARRY MALICIOUS INTENT** depending upon the thing. Know the goddamn difference. चिन्नु न जान्नु ढुङ्गा ले हान्नु । हावामा तेस्सै वाइयात कुरा लेखेको छ अनि बुरुक्-बुरुक उफ्रेको छ। के हो कसो हो थाहा छैन तेस्सै लेख्यो हिरो भयो। Do you know it made me go for 4 suicide attempts. I was depressed after the incident and was brainwashed several times, was left unproductive, throw my things away. Just think, research, and take help from professionals before you end up posting anything when it comes to something like blaming or thanking people off the Internet. Hope you and other content creators got it.

Also, another thing to note **there is no Bramhapichas** it was just me saving a handle (nickname) for myself for the next possible thing. Another thing is, I have no clue who on Earth Bramha is 😕 , And since I've gone through a hell of a lot of stuff, I don't have any plan of doing something similar ever again.

Let's get back to the incident, I then decided to make more fun of Mr. Mugger so I tweeted another quote by mentioning him:

<img src="/static/img/tweet_3.jpg">

I was literally lurking for some activities and since there was not even a single activity. I decided to reply to Mr. Mugger telling him data isn't just beautiful, it's entertaining too.

<img src="/static/img/tweet_4.jpg">

Then, I just slept off after having dinner thinking might get some reach. The next day, in the morning it did get some reach but it didn't manage to reach Vianet (that it was breached) People had visited the expiring paste-bin and downloaded the data. But, no one reported it to Vianet or none of Vianet's Official were aware of the incident. Since I wanted it to be known by Vianet. **I just forgot for a while that it might be bad if data would be in the wrong hands**, and I made a plan to host it on the [Dark Web](https://en.wikipedia.org/wiki/Dark_web) (Tor) Since, downloading data off the Tor would be slow. I filtered a few too obvious information as well as other stuff which one might be interested in (example: reward_points, secondary phone number, etc..) and made it a compact CSV ready to distribute. Here, I could have erased few characters off the CSV making it fit for "privacy-conscious" people **yelling their lungs out at my tweets** but at that specific moment, all I wanted was it to be visible to Vianet while maintaining my anonymity so I just forgot to do so. Then, I started to work on hosting an [onion](https://en.wikipedia.org/wiki/.onion) link And, after I'd written HTML/CSS for it along with the [Checksums](https://en.wikipedia.org/wiki/Checksum) of the CSV dump calculated. I hosted it on the onion router with an onion link.

##### In easy words, people had downloaded the dump but Vianet didn't know about it. So, I'd just filtered the data a bit and hosted it on the dark web. Then tweeted the following:

<img src="/static/img/tweet_5.jpg">

And, I just said that the nation faced the biggest breach in its history but still no one cared with the following tweet:

<img src="/static/img/tweet_6.jpg">

Later, I managed to find Vianet's official Twitter account and mentioned it with the tweet below.

<img src="/static/img/tweet_7.jpg">

## Acknowledgment

My dump was lit like a huge forest fire. I also saw [Nepali Telecom](https://www.nepalitelecom.com/2020/04/vianet-customer-data-leaks-hack.html#:~:text=Meanwhile%2C%20they%20say%20they%20have%20requested%20to%20authorities%20to%20take%20down%20the%20data%20from%20where%20it%20was%20uploaded.) state "**Meanwhile, they say they have requested to authorities to take down the data from where it was uploaded.**" Hello? Did you write this on vodka? Nothing would ever happen even if it's requested to authorities to take the onion link down. Since I'd hosted it on the Tor network. I would have to take it down myself which I did thinking it's enough for the day.

Then, I felt happy that first time I saw Nepali patch a vulnerability within 24 hours. Honestly, it feels really good when someone patches known vulnerability. I was proud to see [the first-ever Nepali breach appear on HaveIBeenPwned.com](https://haveibeenpwned.com/PwnedWebsites#Vianet)

I am being honest, I didn't think of the consequences of letting the breach distribute for almost a day. My family/relatives who'd subscribed to Vianet had equal damage from the breach. I do regret it. And, went into depression afterward thinking it all happened because of me. I wasn't able to talk the way I used to, crack jokes the way I used to, enjoy the moment the way I used to, I was left unproductive than ever before. I was degrading myself day by day. And, did try to surrender to the [Cyber Bureau of Nepal Police](https://nepalpolice.gov.np/index.php/cyber-bureau) but didn't have enough courage to. Later, a few of my friends decided to play the role of a real citizen of the nation and reported it to them which guided Nepal Police to my arrest. They didn't have single technical evidence, it was all based on screen-shots of my conversation with my friends. I am neither mad at them, nor the Police. I am just happy that they helped me get it off my shoulder.

Also, thanks to [IctFrame](https://ictframe.com/) for the screen-shots, as I'd erased all of the pieces of evidence by shredding data available within the Hard Disk. It literally took 2 days to get rid of the data by wiping and writing random data to all of the blocks of the Hard Disk several times. And, I knew after such an incident people would report twitter for the account. And, it was part of my plan to get the Twitter account suspended forever.

Also, I do not think that big tech shots of Nepal are still aware or they care about the security. Nepal should introduce a law to allow lawsuits based on hacks they go through. Both of the parties, the hacker and the vulnerable company should get into trouble then only I think the vulnerabilities would get patched in a good manner.

Also, it feels good to see my browser warn me before I visit dangerous places. Not the actual number but okay, maybe they were counting it from unique email and ignoring all emails from @**vianet.com.np**'s domain. If they had counted it from a phone number that people rarely use on the Internet, it would look huge.

<img src="/static/img/browser.jpg">

And, as proof that I'm the real dude who did all of it. I've embedded a video below:

<video src="/static/vid/hacking.webm" autoplay loop>
