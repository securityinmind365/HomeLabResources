# HomeLabResources
List of resources for buiding a home lab


Pay what you want book
Building Virtual Machine… by Tony Robinson 
Learn everything there is to know about building and maintaining your own home or workplace virtual lab environment on the most popular hypervisors today!
https://leanpub.com/avatar

Great run through of building a lab influenced by Tony above.  Lots of links and suggestions and lessons learned.
https://www.netsecfocus.com/home/lab/2020/09/21/Tjnulls_guide_to_building_a_Home_Lab.html

AutomatedLab is a provisioning solution and framework that lets you deploy complex labs on HyperV and Azure with simple PowerShell scripts. It supports all Windows operating systems from 2008 R2 to 2019, some Linux distributions and various products like AD, Exchange, PKI, IIS, etc. 
https://github.com/AutomatedLab/AutomatedLab

How to Build a Home Lab
Black Hills Information Security webcast
https://www.youtube.com/watch?v=_Ih_wjHafrM

More good stuff from Black Hills instructions and information for building a lab environment.
https://www.blackhillsinfosec.com/how-to-deploy-windows-optics-commands-downloads-instructions-and-screenshots/


SANS: Building an Enterprise Grade Home Lab 
https://youtu.be/jnotvkoUF9U

SANS: Extending Your Home Lab to include Cloud   https://youtu.be/j69DRB4WGeY

Other resources for free/cheap software referenced in the SANS webcasts:   https://github.com/aboutsecurity/blueteam_homelabs

SANS: Building Your Own Super Duper Home Lab
https://youtu.be/uzqwoufhwyk

HAK5:  Building a Home Lab Virtual Server Quick and Dirty - Hak5 1819
https://youtu.be/9SpQ1fRQAto

Tyrone E. Wilson
Building an Effective Cybersecurity Learning Environment
https://www.youtube.com/watch?v=ZYAgyZ7RZm8
Hands-On Learning: How and Why You Should Build a Home Lab
https://www.youtube.com/watch?v=CL2Ng191KQE

Filtering DNS and HTTPS Traffic on pfSense
https://docs.diladele.com/tutorials/filtering_https_traffic_squid_pfsense/index.html

Splunk Attack range
https://github.com/splunk/attack_range

Purple Cloud - An Infrastructure as Code (IaC) deployment of a small Active Directory pentest lab in the cloud. The deployment simulates a semi-realistic corporate enterprise Active Directory with a DC and endpoints. Purple team goals include blue team detection capabilities and R&D for detection engineering new approaches. 

https://github.com/iknowjason/PurpleCloud

BadBlood - BadBlood by @davidprowe, Secframe.com, fills a Microsoft Active Directory Domain with a structure and thousands of objects:  
https://github.com/davidprowe/BadBlood


The UK National Cyber Security Center has a great project for small/home offices to help them get started with logging.  This can be used for home labs as well. Not a full SIEM solution, but a start.
https://github.com/ukncsc/lme


Powershell script to create AD Domain Controller and Workstation     
https://browninfosecguy.com/Active-Directory-Lab-Setup-Tool

Direct link to download free Microsoft Hypber-V server    
https://www.microsoft.com/en-us/evalcenter/evaluate-hyper-v-server-2019

Great instructions for building ELK and Wazuh home lab:  
https://github.com/watsoninfosec/ELK-SIEM

Justin Henderson, the author of SANS SEC555, SEC530 and other courses is doing a series on building a home lab.
https://youtube.com/playlist?list=PLIQlcXRut9IPF8cJSSf0-BsoFy_1SOGYQ

A guide on building a DIY SIEM at home by James Smith @DFIRmadness
https://dfirmadness.com/building-a-siem-at-home/

Another great blog with lots of details and links
https://www.offensive-security.com/offsec/tjnulls-guide-to-building-a-home-lab/

A video from Black Hat Trainings in 2020
https://www.youtube.com/watch?v=X3TyFji-jEw

Building ELK SIEM 
https://youtu.be/HI072Rkthoc  pt 1
https://youtu.be/mIXf2k9BQ3k  pt 2

Building ELK SIEM in blog format
https://www.hackingarticles.in/threat-hunting-log-monitoring-lab-setup-with-elk/

Cyberrange options to deploy in Azure
https://levelup.gitconnected.com/building-azure-cyber-ranges-for-learning-and-fun-9df1debb2eae?gi=e662f36c25fb

Series of videos for building a home lab by Day Cyberwox @DayCyberwox:
https://youtube.com/playlist?list=PLDqMNdDvMsRkmtiKcZwbhOz7MeLQE0r3G

Join this talk with SANS Certified Instructor and course author Justin Henderson, as he shares what the steps are in building out a detection oriented blue team lab.
https://youtu.be/EtlI04dJWX4

Great setup script for Windows PCs from https://twitter.com/ajpc500

Wrote a quick and dirty PowerShell script to install Sysmon (SwiftOnSecurity config), SilkService and Winlogbeat, and forward the logs on to HELK. Might be useful for those looking to quickly configure endpoint logs in a lab environment

https://gist.github.com/ajpc500/3a86ba1741d4868b69be5ce3a142d527

From https://twitter.com/HBRH_314:
In this first video of Malware Analysis Fundamentals, we create our analysis environment for safe inspection of malware utilizing Remnux and FLARE VM.
https://youtu.be/whApbC5OvOs

AWS Pen-Testing Laboratory - Pentesting Lab With A Kali Linux Instance Accessible Via Ssh And Wireguard VPN And With Vulnerable Instances In A Private Subnet 
https://www.kitploit.com/2021/06/aws-pen-testing-laboratory-pentesting.html

Podcast/Videos on various topics for building stuff for your lab:
https://thehomelab.show/

And of course there is at least one homelab reddit
https://www.reddit.com/r/homelab/


Some great resources from Jeff McJunkin

https://bit.ly/kickasslab
https://www.youtube.com/watch?v=KogdkuEbfwc


More free/demo software:

data router/parser/mover  Cribl:  https://cribl.io/download/

Rapid7 InsightIDR Free Trial (SIEM): https://www.rapid7.com/try/insightidr/

A Guide to log formats:
https://www.graylog.org/post/log-formats-a-complete-guide

Generating data for you lab

Generate suspicious activity
https://www.activecountermeasures.com/threat-simulation-overview-and-setup/

Generate fake user activity
https://github.com/ubeeri/Invoke-UserSimulator

A quick and dirty HTTP/S "organic" traffic generator.    https://github.com/philhagen/web-traffic-generator

Some other ways to generate data to be collected by your SIEM

https://pypi.org/project/log-generator/

https://logs.to/

https://nxlog.co/documentation/nxlog-user-guide/generating-test-data.html

https://github.com/tdunning/log-synth
