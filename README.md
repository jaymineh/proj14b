# Project 11 - Ansible Configuration Management

In this project, I implemented a solution using Jenkins & Ansible. Here, when code changes have been reviewed and pushed to the main branch, Jenkins runs a job and the new changes are dumped to the Jenkins server (which is acting as a bastion host). From there, the Ansible script is run against the respective machines. SSH agent is also configured here to allow ansible connect to the remote servers.

Kindly check `project.md` for more information.
