# Manage_repo_with_Jmeter
This repository created to manage repositories using Jmeter and Github api's

Prerequisites: you need to genarate access token before runnin these scripts

I have create two Jmeter scripts to manage github repositories without loin to github sites by using github API's.

The above two scripts can

1) create new repo
2) delete repo
3) get repo list
4) one script can add or push file to repository , I have used base64 encoded mechanism to encode file data before pushin to github server. you have to pass path of the file and encoded data through api endpoint so that it will create file in your repository.

Note: Please do not run any load usin these scripts, I have prepared just self exploratory pupose. Than you for your understanding.
