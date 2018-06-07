# Week10Lab-and-Project

# LAB - Gone Phishin

## Milestone 0: Kali gone wild 


<a href="https://imgur.com/yQBWLQE"><img src="https://i.imgur.com/yQBWLQE.png" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. configured the settings in virtual box of the VM and switch the Network adapter settings value from NAT to Bridged mode.
          2. opened Virtual Machine through virtualbox
          3. opened terminal window and typed configured the setting to disable IPv6
          
## Milestone 1 : Hello, SET

<a href="https://imgur.com/xgc1GtX"><img src="https://i.imgur.com/xgc1GtX.jpg" title="source: imgur.com" /></a>
<a href="https://imgur.com/4RCPGg5"><img src="https://i.imgur.com/4RCPGg5.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Created a Gmail email account (throwaway email).
          2. Proceeded to download SET into KaliLinux
          3. Proceeded to use SET using their social engineering attacks walk through
          4. Used the throw away email to use in a mass mailer attack on only a single email address which was my throw away email.
          5. Verified that it worked.
## Milestone 2: Try a Real Payload

<a href="https://imgur.com/lppBSz4"><img src="https://i.imgur.com/lppBSz4.png" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Essentially the same thing but with a set payload from SET.
          2. Went to select Spear-fishing attack vectors in SET.
          3. Selected Create a file format payload and chose a payload that dealt with an exploit involving stack buffer overflow.
          4. chose an option that would give control of the target ( if successful).
          5. SET returned an error message meaning that the attack was unsuccessful, meaning that the host Google, was scannning the attachment for malicious signatures and prevented from sending the mail.
          
## Milestone 3: Fakebook

<a href="https://imgur.com/DBf9u3q"><img src="https://i.imgur.com/DBf9u3q.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Used SET to recreate a facebook related login page.
          2. This was done by going through the social engineering attacks option in set and and selecting website vecctors.
          3. Then simply selecting the credential harvester attack method and selecting site cloner, I had to input an IP address that the intended fake website will post to which was the IP of the virtual machine.
          4. Entered the site i want to clone, which was facebook site.
          5. clone website was created and was accessible through the browser using just the localhost to reach it.
## Milestone 5: cleanup

<a href="https://imgur.com/tSO9QJI"><img src="https://i.imgur.com/tSO9QJI.png" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Simply shut down the machine
          2. undid the steps from Milestone 0
          3. switched bridged mode back to NAT through the virtual box settings of the virtual machine I was using.
## Milestone 6: SE in Situ

### What could the user do to mitigate this, making a successful login impossible for the attacker even with the credentials? (Hint: FB offers this as an option; not all sites do)

To offer two-factor authentication, therefore if the attacker is able to successfully login he would also have to get cleared for the two-factor authentication step. 

### Why might the username/password still be of value to the attacker even if she can't use them to login to Facebook? (Hint: think about how users come up with passwords)

This would still be valuable as the attacker can simply use the same password or username ofr other sites such as twitter, gmail, icloud, etc. this could eventually lead to a compromise of accounts just like the suggested reading about the victims icloud and amazon account hack.

# Assignment Week 10 Project : the Dark Side

## Part 1: the (broken) Internet of Things

## Challenge 1.0: Hello Shodan

<a href="https://imgur.com/r01fZpk"><img src="https://i.imgur.com/r01fZpk.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Followed the link provided in the codepath assignment page.
          2. Used a throwaway email to create Shodin Account

## Challenge 1.1: Webcams

<a href="https://imgur.com/WhkpfdN"><img src="https://i.imgur.com/WhkpfdN.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
         1. Went to the suggested site and took look of th example of the AXIS search query on Shodan
         2. Became familiar of the default logins that are associated with many manufacturers and how this can cause a problem since owners of the manufacturers webcam products are not successfully changing their passwords.

## Challenge 1.2: filtering

<a href="https://imgur.com/CX6u6tL"><img src="https://i.imgur.com/CX6u6tL.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Simply went to and searched for a specific webcam that identified a webcam from a zoo located in Japa.
          2. Searched for a search quiery involving the specific hostname that was given.
          3. narrowed results by inserting the port number that was exposed which was port 8080
          4. Search resulted in 5 options neither ended up being the zoo webcam.
          5. searched the hostname and also inputted "camera" to see if zoo webcam would show. which it did show up a result with the intended search quiery but was not able to proceed any further since it asked for a login, figured it was a wrong webcam.
          6. ended with no zoo webcam.
## Challenge 2.0: Tool Up

<a href="https://imgur.com/smm76PZ"><img src="https://i.imgur.com/smm76PZ.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Created a virtual machine running a tails ISO image that was downloaded.
          2. Tails ISO image that was suggested in the codepath assignments page gave an error message and did not provide the download.
          3. Was able to locate the Tails ISO Image through the main homepage and proceeded with the donwlaod .
          4. After creating the virtual machine, simply just configured the setting in virtual box to allow a shared clipboard between the host machine and the virtual machine.
          
## Challenge 2.1: Switching Circuits

<a href="https://imgur.com/plZJ6uE"><img src="https://i.imgur.com/plZJ6uE.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. opened the tor browser through the virtual machine.
          2. understood the process of how tor routes its traffic through a series of nodes, mainly understanding that tors layers or nodes don't really know the whole path a packet has taken as it only knows the node before and fter  but never the whole path.
          3. completed the challenge that involved reaching the craigslist site by individually reswitiching the circuits until i got accessed to the site.
          
## Challenge 2.2: Onions

<a href="https://imgur.com/tDfd9QZ"><img src="https://i.imgur.com/tDfd9QZ.jpg" title="source: imgur.com" /></a>
- [x] Steps to recreate:
 
          1. Viewed the deepDotweb site that was provided.
          
## Challenge 2.3: Into the Darkness

<a href="https://imgur.com/UvrqlLu"><img src="https://i.imgur.com/UvrqlLu.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. tried to access the hidden wiki link that was provided but failed to load.
          2. viewed the anarchist bookstore and also the clearnet site ahmia.fi 
          
## Challenge 2.4: How (Not) To Get Busted

<a href="https://imgur.com/6R9XMtE"><img src="https://i.imgur.com/6R9XMtE.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Understood that even while using tor you can still be identified through fingerprinting.
          2. Proceeded a walkthrough into clearing the cookies and cache by selecting a new identity through the tor browser.
          3. this was done through the security settings.
## Challenge 2.5: Then Came The Money

<a href="https://imgur.com/BVFgBh8"><img src="https://i.imgur.com/BVFgBh8.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. I learned that satoshi nakamoto was a mysterious individual who invented bitcoin.
          2. Launched the VMs electrum Bitcoin wallet, and proceeded to create a allet.
          3. selected the wallet and entered the address that was suggested,
          4. viewed the amount of bitcoins in that read only wallet.
          
## Challenge 2.6: Stay in School, Kids

<a href="https://imgur.com/SQJHhtV"><img src="https://i.imgur.com/SQJHhtV.jpg" title="source: imgur.com" /></a>

- [x] Steps to recreate:
 
          1. Visited the site provided that showed what most people use the darknet for, whicich is the black market.
          2. Looked around and saw the dangers of the black market.
          3. understood that it works through a ebay style reputation system where you can simply see a user with good reviews which might infer that they are a trusted seller.
          
## License

    Copyright [2018] [Reymundo Reza]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
