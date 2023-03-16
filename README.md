<p align="center">
<img src="https://imgur.com/pS68rrA.png alt="Traffic Examination"/>
</p>
<br />
<br />
 
<h1>Tenable Nessus Essentials Basic Scan Tutorial</h1>
<br />
<br />


<h2>Environments and Technologies Used</h2>

- Windows 10 (Local)
- Tenable Nessus 
- Windows 10 Virtual Machine Running in Virtual Box
<br />
<br />


In this tutorial, I will demonstrate a basic scan using Tenable Nessus on a Windows 10 virtual machine using Oracle Virtual Box. This tutorial assumes you already have Nesuss installed and a Windows 10 instance running on a local virtual machine or in the cloud.
<br />
<br />

<h2>Main Steps of Deployment and Scan</h2>
<br />
<br />


Step 1. Get the ip address of the Virtual Machine you have running by opening a command window and typing the ipconfig/all command
<br />
<br />

<p align="center">
<img src="https://imgur.com/g84UVyf.png alt="Traffic Examination"/>
</p>
<br />
<br />

1b. Not the ip address of the virtual machine
<p align="center">
<img src="https://imgur.com/57qhqzY.png alt="Traffic Examination"/>
</p>
<br />
<br />
 

Step 2. Navigate to the url of your Nessus install and sign in. (Most of the time it's https://localhost:8834/#/)
<br />
<br />

<p align="center">
<img src="https://imgur.com/b7Kc2cl.png alt="Traffic Examination"/>
</p>
<br />
<br />

Step 3. Once you sign in click new scan at the top right corner
<br />
<br />

<p align="center">
<img src="https://imgur.com/qRo4PuU.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 4. Click Basic Network Scan from the scanner menu 
<br />
<br />

<p align="center">
<img src="https://imgur.com/lJtCGxb.png alt="Traffic Examination"/>
</p>
<br />
<br />

Step 5. Fill in a name, choose a folder, a description (optional) and the ip address of any target you want scanned, then click Credentials (if you wish for a deeper scan into a target)

<p align="center">
<img src="https://imgur.com/1npWpsm.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 6. Click Windows to open up the crednetial settings

<p align="center">
<img src="https://imgur.com/aVqTtNd.png alt="Traffic Examination"/>
</p>
<br />
<br />



6b. Enter in the credentials of the machine you wish to scan deeper into and click save at the bottom 

<p align="center">
<img src="https://imgur.com/vLsOX37.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 7. Click the play button all the way to the right to start the scan (as pictured below)

<p align="center">
<img src="https://imgur.com/wDedJFe.png alt="Traffic Examination"/>
</p>
<br />
<br />

7b. As the scan proceeds, you will see a spinning circle (as illustrated below). Click the scan title to see any information being populated.

<p align="center">
<img src="https://imgur.com/7efNG06.png alt="Traffic Examination"/>
</p>
<br />
<br />


7c. Click the vulnerability info to see any information being reported

<p align="center">
<img src="https://imgur.com/VbP9hsm.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 8. Once you see the Vulnerability information, if there are multiples in a folder you can click the folder to see futher information

<p align="center">
<img src="https://imgur.com/R0Eq4bn.png alt="Traffic Examination"/>
</p>
<br />
<br />


8b. Vulnerability information is displayed when clicked 

<p align="center">
<img src="https://imgur.com/wjEPj7X.png alt="Traffic Examination"/>
</p>
<br />
<br />

8c.

<p align="center">
<img src="https://imgur.com/bNQEeZJ.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 9. (Optional) To save and export a report, click Back to Vulnerabilities at the top left and click the report tab (top right)

<p align="center">
<img src="https://imgur.com/rloHmAt.png alt="Traffic Examination"/>
</p>
<br />
<br />

9b. Choose your report type (CSV or HTML)

<p align="center">
<img src="https://imgur.com/YlWSPYC.png alt="Traffic Examination"/>
</p>
<br />
<br />



9c. For an HTML Report, choose the option and settings, then click generate report at the bottom as displayed below 

<p align="center">
<img src="https://imgur.com/YlWSPYC.png alt="Traffic Examination"/>
</p>
<br />
<br />


9d. For a CSV report, choose the option for CSV and the settings, then click generate report at the bottom as displayed below

<p align="center">
<img src="https://imgur.com/dzcDnSV.png alt="Traffic Examination"/>
</p>
<br />
<br />










