# SymantecProjects
Documentation of the projects undertaken as part of internship semester at Symantec


 <b>Project 1 : File system monitoring for Windows machines in enterprise network :</b>
 
 It is an utility that makes it easy to monitor folders, subfolders and individual files for changes during a specific time in an enterprise network.  This module targets all windows platforms and provides you with a comprehensible list of all the files that have been created, modified, deleted along with the type of changes that have occurred. It works with specifying a target along with a template where desired monitoring parameters are configured. Various checks include :   
changed files,new files, removed files, changed ownership, changed permissions , changed signature and modification time . Hence, it can also be used to track any changes made by any malicious software in an enterprise network.
Working of File watch module: When the file watch module is first run, a snapshot is taken. The next time the module is run, it will again take a snapshot and report for all the files which have been modified by comparing the two snapshots.
Example: The /etc/system file has been specified in the file watch template for Windows. On the first run of the module, a message indicating that snapshot is taken will be in the results. If the file has not been changed on the subsequent run, it will report no problems found. If changes are made to the content of /etc/system file, it will report that the /etc/system file was modified.  
I had worked in all stages of this project including coding as well as testing. The coding was done in C++ . 
Concepts learned :
1.	C++ STL
2.	Win32 API to create processes
3.	Base64 encoding/decoding in C++
4.	File handling to read CSV files in C++

<b>Project 2. Conversion of Security Content Automation Protocol benchmark to proprietary format: </b>
The utility is used for converting the Windows Security Content Automation Protocol (SCAP) standards to the proprietary Control Compliance Suite’s standards in order to automate the high-level monitoring of a system’s security in an enterprise network.
The Security Content Automation Protocol (SCAP) is a protocol that standardises the format by which software flaws and security configurations are embedded in XML . Essentially , this is a means of establishing some automated “on/off” switches when checking to see if a server or desktop is compliant with the standard in question. The National Institute of Standards and Technology (NIST) is the U.S. government content repository for SCAP .They measure systems to find vulnerabilities and offer methods to score those findings in order to evaluate the possible impact.
In the product I was working on, i.e., Control Compliance Suite, proprietary standards are used for determining the compliance of windows machines in the enterprise networks through a console.  User can import these standard in Control Compliance Suite console and run a Data collection-evaluation-reporting job using them for the network machines. 
These standards are primarily based on SCAP contents. However, the format is such that it can be understood by the Standards Manager. For example, in these standards we have checks. Each check has the data collection section which indicates what data needs to be collected for the check and an evaluation section which indicates how to evaluate on the collected data. Based on the evaluation, the check gives a result of pass/fail. In the end, a risk score is calculated for each check and an overall compliance score is calculated for the machine specifying its vulnerability level.

To automate the conversion of SCAP standards to the proprietary standard a tool was required and this was my project. Concepts learned :

1.C# and .Net basics
2. XML parsing, using Collections and File handling in C#
3. Security Content Automation Protocol (SCAP) Concepts
4.Open Vulnerability Assessment Language(OVAL) Concepts

