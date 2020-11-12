# captcha_solver

Group Members: Sonya Cirlos, Melissa Cavazos, and Hasbanny Irisson

Topic: Text-based CAPTCHA attack with deep learning 

Paper: Yet Another Text Captcha Solver: A Generative Adversarial Network Based Approach 
https://eprints.lancs.ac.uk/id/eprint/126984/1/ccs18.pdf

Short Discussion of paper:

Today, there are various deep neural network approaches to attack and/or bypass a CAPTCHA and most require a large number of labeled CAPTCHAs to become successful CAPTCHA solvers. Because there have been various successful captcha attacks, captchas are being developed with more security features. In this paper, Ye and research team present their captcha synthesizer to produce the large amount of captcha images needed using generative adversarial networks or GANs. The team also proposes the first GAN text-based captcha solver and prove how it outperforms other captcha solvers in attacking even the text  captchas with advanced security features. 


Proposed design of project: 

Our project consists of developing our own text CAPTCHA solver/attacker with deep learning and modifying it to include captchas with a variable number of characters and captchas with multiple words.These modifications were suggested in the paper as extensions that would make the author’s solver even more effective. We will be applying these modifications to our deep learning captcha solver. 

1. Build our own text-based CAPTCHA solver using deep learning with help from open-source projects on github. 
2. Compile our training dataset. 
    	- For this step, our training set has to have CAPTCHAs with a fixed number of characters. 
    	- This step will probably be repeated several times to train models with CAPTCHAs of different numbers of characters. 
3. Extend the implementation to include CAPTCHAS with:
    	- A variable number of characters. 
		Predict how many characters are in the CAPTCHA
	- Select a model that has already been trained for that number of characters. 
    - Multiple words.
	- Segment the words in the CAPTCHA to recognize individual words for multi-word CAPTCHA systems. 
