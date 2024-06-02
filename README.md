<a href="https://johnshearing.github.io/">Main list of projects</a>  

**Portable a.i witness attests to humanity, membership, ownership and status without leaking identity or personal data.**

**Problem Statement:**  
Without Revealing Your Identity or biometric data,
Prove You Are Human,
That You Have The Right To Vote In A Given Jurisdiction,
And That You Have Not Yet Cast Your Ballot,

**Background:**  
The last job I had before retiring was chief controls tech at a robotic sort center.
My only job was to keep everything running but I got bored and built an a.i. system to detect bunched up packages and eject them from the system to prevent mis-sorting.

Formerly this was done by humans and they hated the job because it required intense concentration and yet was very boring so it put them to sleep.   

This video was taken while I was training the a.i.    
You can see in the video linked below the poor man falling asleep with the yellow control box in his hand.   

<a href="https://youtu.be/86aRFeI_Tys" target="_blank"><img src="/JobNotForHumans.jpg"/>   

This was the guy responsible for pressing the button 8 hours a day to reject packages from the conveyor if they were all bunched up and clustered together. He was my motivation for building the a.i.. I wanted to relieve him so that he could do a job more fitting for humans.   

The video below shows the a.i. at work.   

<a href="https://youtu.be/Pq97KxsR0aI" target="_blank"><img src="/ClustersDetected.jpg"/>   


If you stop the video at the right moments you can see the clustered packages surrounded by a red bounding box and labeled with the word "Cluster"  
When these are detected, the a.i. triggers a relay in the USB port of the host computer which effectively pushes the same button that the poor sleepy fellow was pushing on his yellow control box.  

![image|1000x406](relay.jpg)  

**The Insight And The Idea:**  
So you may be wondering, what does this have to do with an identity solution that can prove you are human, that you have the right to vote in a given jurisdiction, that you have not yet cast your ballot, and all without revealing your identity or biometric data?

The key insight is that the output of the a.i. is not the video. That video was collected to help me see how the a.i. was doing during training but normally that video is not collected and there is no monitor present.

The output of the a.i. is the relay in the USB port that accepts or rejects packages **without revealing any information about the packages** except for the one thing it is trained to detect, whether or not the packages are clustered.

In this case the a.i. is trained to detect clustered packages and that is all the a.i. reveals about the packages even though it sees the names and addresses on the packages and sees its dimensions as well.

And that is the insight. This type of a.i., known as a classifier, can only say whether or not the input matches one or more of the classes it was trained to detect. Nothing else is revealed. No information is leaked.

So with just a little bit of stretching we can imagine an a.i. asking a prospective voter to wiggle their nose and pull on their ear and such in some random order to prove they are human. Fingerprint readers, signature recognition, and voice recognition could be used as well with no information leakage as you will see.

Then the a.i. asks to see the individual's driver's license and checks that it matches the features of the individual to prove they are a citizen of the jurisdiction.

Finally, it hashes the individual's driver's license number and provides this to the authority.

The authority checks that no one with that hash has already voted.

That all seems pretty doable but you are probably thinking: "Why would we trust that the ai is not keeping an image of the drivers license or the citizen's biometric data?"

We trust the a.i. because the a.i. is owned and controlled by the individual not by the authority. And it runs behind secure hardware on the individual's phone or similar sized handheld device. 

A.I.s are already built into many brands of smartphones for helping with photos and other tasks. So the tech is already here and largely deployed. 

Everybody has their own open source government certified a.i. which is nothing more than a file containing the pretrained neural network and another file containing a program to run it.

Both files would be identical to the same files on every other citizen's phone and the hash of the files would prove it.

These two files and the process is sequestered behind trusted hardware on the owner's device and reveals nothing but the answers to questions asked by the owner.
Am I human?
Am I a citizen?
What is the hash of my drivers license number?
and so on.  

So in much the same way individuals now have hardware wallets as witnesses to prove we have the right to move funds on a blockchain, We will soon own certified a.i. witnesses running on our devices to prove we are human, to prove we are citizens with specific privileges such as uncast ballots or perhaps unclaimed rations, all without leaking our identities or our biometric information.

If the training data is open source, and we all use the same seed for the pseudo-random number generator used to create the weights, and if the hardware is the same, and if we train the model on the data the same number of iterations, then it should be possible for citizens to produce the exact same neural network file with the same hash.  

This would prove there is nothing malicious in the neural network file and we would know exactly what data was used to train it.  

With this system, the a.i. doesn't retrieve anything from the Internet, nor does it look up any personal information on your phone.  
The a.i. is just examining your biometrics and testifying that you are human without revealing the biometrics and without keeping the data.  
Then looking at your driver's license and testifying that it is from the province and that it matches your biometrics without revealing your identity or keeping the data.  
And finally hashing the driver's license number and giving that hash to the authority to confirm that no one with that hash has already voted but without revealing your driver's license number.  

It wouldn't matter if you lost your phone along with the a.i. because it doesn't store any information about you.  
The only reason to use an a.i running on your own phone behind trusted hardware is to ensure that no one is keeping your biometrics or an image of your driver's license.  

The a.i. is only a certified trusted witness known by the state to give truthful answers about the information it is looking at.  
It is up to the owner to decide what questions to ask.  

***Proving Humanity, Citizenship, and whether or not a citizen has already cast a ballot all without revealing identity or biometric information remains an unsolved problem.***

***Who will be the first to develop an open source, (citizen owned), a.i. identity solution for voting, governance, and financial systems - perhaps picking up the job where hardware wallets and other identity systems fall short?***

Video by Charles Hoskinson on the importance of open source citizen owned AI  
https://www.youtube.com/live/kWtco6wn67E  
While Charles surely knows nothing about this idea, his recent video is clearly an endorsement for open source citizen owned a.i..  
Better, he has called for hybrid developers who are fluid in both blockchain and a.i..   
 
This pointer, provided by Charles led to all of the following resources below:  
These resources create a path to move from idea to a workable solution.  
https://erichartford.com/uncensored-models   

This resource is by far the most interesting.  
**Google Admits It Cannot Complete With Free and Open Source a.i.**   
https://www.semianalysis.com/p/google-we-have-no-moat-and-neither  

https://erichartford.com/running-dolphin-locally-with-ollama?source=more_articles_bottom_blogs  

https://erichartford.com/built-with-dolphin?source=more_articles_bottom_blogs  

https://erichartford.com/dolphin-25-mixtral-8x7b?source=more_articles_bottom_blogs  

https://youtu.be/SGkaWMDKM9g?si=K641NqiefZhiRoq7  

https://huggingface.co/  


**Soon Running An a.i. Will Not Require GPUs.  
This will open the process of running LLMs to regular citizens in the open source community that don't have access to expensive GPUs**  

https://youtu.be/MXWlB9nDAFU?si=uiLs__JX72egVikv

https://youtu.be/Gtf3CxIRiPk?si=Odc_3pgUWTsDbgFO  

https://youtu.be/jLg2ycOgSBU?si=wlJJc9GXbVsA8aH9  

https://youtu.be/Zp8mKlKLphU?si=L-4Ge8YYq_ysC22S  

https://arxiv.org/pdf/2402.17764.pdf  

https://arxiv.org/pdf/2310.11453.pdf  

**Special Ternary Hardware Must Be Developed In Order To Take Full Advantage Of The Process**  
https://g.co/gemini/share/4a78735a9115


I haven't heard anyone talking about this yet but I would expect to hear a lot of buzz about this soon:

The recent advance in machine learning mentioned above should break down the barrier to using a.i. together with zero knowledge proofs. 

**First the application to Sovereign KYC and Anonymous Voting:**
Imagine a human shows up to vote. 
The human is told to make a video using their smartphone where they perform a random set of instructions like repeating a unique sentence. This records biometric data such as appearance and voice. Then the human takes a photo of their own driver's license. The video and photo are encrypted into a Zero Knowledge Proof while still on the phone and then the proof is emailed to the government a.i.. The a.i. provides a proof to the voting authorities that the classification it returns (Citizen who has not voted or Citizen who has already voted) has been run on the government's approved neural network.
**The a.i. classification and following zero knowledge proof is processed without ever decrypting the message**.
So the government a.i. certifies that you have the right, or do not have the right to vote, without ever knowing who you are.
Sovereign KYC and Anonymous Voting

The problem which prevents Zero Knowledge Machine Learning is that a.i. models must be translated into zkCircuits. And a.i. models currently use expensive floating point arithmetic to manage the weights whereas zkCircuits require smaller fixed point notation. This makes the translation prohibitively expensive for all but the smallest a.i. models. It just dawned on me that the solution may be very close at hand. Recently I reported above that it is now possible to run a.i. models using fixed point notation. The big news was that this makes it possible to run a.i. models without expensive GPUs. But there is another benefit that I have not heard anyone talking about yet - Now a.i. models can be run using the exact same type of numbers which are required to translate them into zkCircuits. So we now may be very close to Sovereign KYC and Anonymous Voting using Zero Knowledge Machine Learning (ZKML). And because expensive GPUs are not required, anyone can play! I am going to jump in and learn about running an a.i. model using fixed point notation math and converting it to a zkCircuit. I will report my progress as things unfold. These are exciting times with endless opportunity for all of us.

