# Migrate to new GITHUB AUTH
## What happened to my GITHUB?


On August 13th Github offically depreceated the support for password authentication.  This means anyone who has tried to push code to git will see the following lovely error
<img width="973" alt="githubError" src="https://user-images.githubusercontent.com/38140787/129492976-0bc70877-f74d-498e-8edf-f11f5d012832.png">

## Enough talk, Fix my Github.

Ok.  

In order to fix our github we need to perform the folliwing:

   ### navigate to our github account: https://github.com/
   ### Access `my account` >>> `settings` >>> `Developer settings` >>>  `Personal Access`
   <img width="239" alt="Screen Shot 2021-08-15 at 1 26 08 PM" src="https://user-images.githubusercontent.com/38140787/129493948-67dd6487-8c12-4bff-9f42-7e5fd8831f88.png">
<img width="290" alt="Screen Shot 2021-08-15 at 1 26 18 PM" src="https://user-images.githubusercontent.com/38140787/129493950-2434bb6f-c2f9-4f81-9d17-3626838aae4d.png">

   ### Click `GENERATE NEW TOKEN` - should be something like : `ghp_sFhFsSHhTzMDreGRLjmks4Tzuzgthdvfsrta`
   <img width="729" alt="Screen Shot 2021-08-15 at 1 26 34 PM" src="https://user-images.githubusercontent.com/38140787/129493967-fa26658a-e7d3-4376-aafb-7882136a605b.png">

   <img width="588" alt="Screen Shot 2021-08-15 at 1 27 09 PM" src="https://user-images.githubusercontent.com/38140787/129493961-50e65447-22f5-4a47-bd42-ba904b0d7b77.png">

   ### COPY the token AND SAVE IT SOMEWHERE SECURE - github WILL NOT allow you to see this token again
   ### For MAC OS users - open finder and search `Keychain access` and open the app
   
   ### Search for `github.com` 
   ### edit the password to your new key
   ### navigate to an existing repo and paste the following command to reset credentials `$ echo url=https://account@github.com | git credential reject`
   ### Commit some changes - add and push.  
   ###  When prompted - enter your `github username` and paste the new `access token` for your password
   ### Conquer the tech industry as you see fit

Keep in mind that your access key will only last for 30 days and we will need to be updated monthly perfmoing the abovementioned steps.  Happy Hacking ya'll!!





<img />
