 marketpeak e-commerce platform deployment using git amazon linux ami and AWS
 =============================================================================

 [![marketpeak_e-commerce]](http://3.88.168.107/2130_waso_strategy/)
 [![git url]](https://http://3.88.168.107/2130_waso_strategy/)

 this an e-commerce website thats focus on providing the best quality and affordable household products

 ## IMPLEMENTING GIT VERSION CONTROL

 * initialized a git repository by making a directory called marketpeak e-commerce
 * added website file to the git repository
 * set up your git global configuration using your email and username
 * committed the changes made, added a well explained comment describing the nature of the changes made
 * created a new repository name marketpeak ecommerce without initializing with readme,gitignore and licence
 * linked my local repository to my github remote repo
 * then pushed to the github repo

 ## AWS DEPLOYMENT

 * set up my ec2 instance on my aws account using amazon linus AMI
 * connect to the instance using ssh on your terminal
 * clone the repository on your linux server using ssh or http after generating ssh keypair using ssh-keygen and adding it to your github
 * install a webserver (apache http server(httpd))
 * started and enabled the webserver
 * configured httpd for website by preparing the web directory i.e clearing the default httpd directory and copy marketpeak_e-commerce to it

 ## CONTINOUS INTEGRATION AND DEPLOYMENT
 * created a new branch called development for new feature and fixes
 * made the necessary changes stage it,commit and push to the remote repo
 * created a pull request review the changes and merge into the main branch
 * also merged in the local repo to correspond with what i have in the remote repo and the pushed it to github

 ## DEPLOYING UPDATE TO THE PRODUCTION SERVER
 pull the latest changes on the server by sshing into the ec2 and then navigated to the website directory.reloaded the server to effect the changes and then texted if it worked

 **the table below includes problem face during the course of the project and how i troubleshooted or fixed it*
 ===================================================================================================================

 | **problem** | **solution/troubleshoot** |
 | :---------- | :-----------------------: |
 | i had issues while i was trying to test the website with the ec2 public ip | i fixed it by adding the name of the directory to the ip and then run it and it worked |
 | i encountered difficulties trying to push to github after merging my development branch into the main branch | i fixed it by discovering there was a conflict then i pulled and pushed back
  
