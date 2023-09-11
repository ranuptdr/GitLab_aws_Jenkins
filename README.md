Instructions for GitLab

git config --list
git config --global --unset user.name
git config --global --unset user.email
git config --global --unset credential.helper
cmdkey /delete:LegacyGeneric:target=git:https://github.com
git config --global user.email "anildalar8888@gmail.com"
 git config --global user.name "anildalar8888"


Server
	1. Username and Password (Github)
	2. SSH key               (GitLab)

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

# Start the SSH-Agent (if not already running)
eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_rsa

cat ~/.ssh/id_rsa.pub

Copy

 Log in to your GitLab account.

Go to "Edit Profile" > "SSH Keys" in your GitLab account.

https://gitlab.com/-/profile/keys

Paste the copied SSH key into the "Key" field and give it a meaningful title.
Click the "Add key" button.



git clone https://gitlab.com/anildalar8888/reactjenkins11.git
or
git clone git@gitlab.com:anildalar8888/reactjenkins11.git

https://jennykibiri.hashnode.dev/jenkins-pipeline-to-build-and-deploy-a-frontend-application-on-aws-ec2
'

Contact me on +91-7999452711 for AWS credentials

ssh -i <indentityFile> <username>@<ip/domain>


ssh -i reactjenkins11_pemfile.pem ubuntu@ec2-43-205-128-37.ap-south-1.compute.amazonaws.com
ssh -i reactjenkins11_pemfile.pem ubuntu@43.205.128.37


Lets update the OS


apt upgrade -y
sudo apt-get update -y

systemctl status docker	

sudo apt install -y docker.io

systemctl status docker	

I want to install the jenkins server on our new ec2 instance

1. Direactly Install
2. INstall via Docker Container


docker run -p 8080:8080 -p 50000:50000 -d jenkins/jenkins:lts

http://43.205.128.37:8080/

