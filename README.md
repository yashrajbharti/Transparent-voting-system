# Transparent voting system   
Voting is an essential tool for any democratic government. It is the most important factor to make the goverment for the people, by the people and of the people.   

## Paper ballot system
Traditionally it was the paper ballot system that has been used for a long time by the countries around the world. It's concept is simple, we mark our vote on a piece of paper and put it in the ballot box. At the end of elections the votes are counted and whoever gets the most votes is the winner.  
**Issues :** There are a lot of issues in this system. This system can not be automated and is extremely tedious. We have to go to the venues where the ballot boxes are kept and to wait in long lines. Then there is counting and reporting of votes by hand where their might be a chance the a vote is counted wrong or even not counted at all. The entire process is extremely time consuming and extremely expensive. Also there are malicious actions at many avenues that influence paper ballot elections whether it's using intimidation tactics at the ballot boxes or just stuffing the boxes with fake votes. A highly motivated party or group could find a way to force the outcome they want. Lastly maybe because it's impossible to keep track of our votes or alter our votes we can't be sure that our vote was counted, possibly it was thrown away, maybe you made a mistake perhaps a huge scanal erupted for your candidate later that day, the election isn't over but you already voted, there's no way to change it now.    
So, there are a lot of disadvantages in the paper ballot system, to counter some of these the digtal voting system has been employed.  
  
## Digital voting system  
Just like the paper system the current digital voting is too rudimentary and easily compromised. An attacker can infect specific machines with malware that alters votes or even access the backend to move around and negate votes as they please. There may not be any obvoius or clear examples of these happenings yet but it's a huge point of vulnerability that needs to be addressed.  
So, how can the blockchain help let's have a look.  
  
## Blockchain voting system (Azure Blockchain)    
![](http://www.upl.co/uploads/Screenshot201907261811111564145205.jpg)
  
Voting using blockchain technology and cryptography has a very simple goal, make the election process as transparent as possible. **My Concept :** Any potential voter can securely log in using a webcam and a government-issued ID. After they're done voting, they can use their voting ID to track their vote and check that it has been cast correctly. On top of that, they even give voters the ability to change their vote any number of times until the deadline.   
  
## Elliptical curve cryptography  
![](http://www.upl.co/uploads/Screenshot201907261824351564145890.jpg) 
  
Elliptical curve cryptography or ECC is used to create these votes. ECC is a form of assymetric cryptography that uses two keys: A public key and A private key to encrypt and decrypt data. ECC is similar to a bitcoin where public key cryptography works, keys establish account ownership. Bitcoin transactions must be signed with a private key. Also bitcoin uses elliptical curve functions to generate keys. 
  
![](http://www.upl.co/uploads/Screenshot201907261840501564146700.jpg)
  
**My Concept :** During voter registration the voter creates 2 ECC key pairs, the voter reveals their identity to a verifier who certifies the first key pair, once that's done the voter registers their second key pair anonymously as belonging to their first pair, then the voter cast their virtual ballot and signs up on the vote with their private key. Once the voter is done, anyone can verify whether the signature is valid or not and make sure that none of the votes have been tampered with. All votes can be verified by using voters public keys to see if they came from a legitmate candidate and that's how the blockchain can help create more secure, transparent and cost-effective votes. The blockchain could help amplify the voices of the people by giving them an easier and better way to vote.  
  
![](http://www.upl.co/uploads/Screenshot20190726190232011564148021.jpg)  
