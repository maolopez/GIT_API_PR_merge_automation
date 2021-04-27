# GIT_API_PR_merge_automation

Script for Jenkins to merge back from Hot Fix branch to Master branch and finally to develop branch. 

Using the GIT API, it extracts the "Hot Fix"'s commit SHA in order to merge on Master.

Using the GIT API, it extracts the "Master"'s commit SHA in order to merge on Develop.

There is a block that Notifies Slack's channel through a Webhook token.
