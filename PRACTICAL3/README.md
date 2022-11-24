## Practical no 3
# AIM: Using Cisco Packet Tracer Perform ACL over a network
## INTRODUCTION
### 1)What is static code analysis and its benefites?
Static code analysis refers to a specific type of computer program debugging that can test the code without the need to execute the program.
This enables a thorough comprehension of the code structure and can even help testers ensure that the code remains compliant with various industry standards.
BENEFITS:
It can be done in an offline environment.
It can eveluate all the code in an application, increasing code equality.

### 2)What is Vulnerability?
Vulnerability Analysis is one of the most important phases of Hacking. 
It is done after Information Gathering and is one of the crucial steps to be done while designing an application.
The cyber-world is filled with a lot of vulnerabilities which are the loopholes in a program through which hacker executes an attack.


### 3)What is Flawfinder?
FlawFinder is a python based tool that helps in finding vulnerabilities in a C/C++ source code. 
It examines the source code and gives the list of possible vulnerabilities/flaws in the code as the output.

# IMPLEMENTATION
### Step 1) Install Python and set the path.

### STEP 2) Install Flawfinder
Open commomnd prompt window and execute the following path.
For Windows OS, this tool can be directly installed using the pip command-
```bash
pip install flawfinder
```
After successfully installing it locate it.
```bash
where.exe flawfinder
```
### Step3) Download the flawfinder zip file and keep in drive(extract it)

### Step4) Open the Flawinder folder and run the test. 

# USAGE
### Patchedcode.py Vulnerability_code.py

## Vulnerable code with Output
```bash
ANALYSIS SUMMARY:

Hits = 2
Lines analyzed = 11 in approximately 0.02 seconds (522 lines/second)
Physical Source Lines of Code (SLOC) = 10
Hits@level = [0]   1 [1]   0 [2]   1 [3]   0 [4]   1 [5]   0
Hits@level+ = [0+]   3 [1+]   2 [2+]   2 [3+]   1 [4+]   1 [5+]   0
Hits/KSLOC@level+ = [0+] 300 [1+] 200 [2+] 200 [3+] 100 [4+] 100 [5+]   0
Minimum risk level = 1
```
## Patched code with Output
```bash
ANALYSIS SUMMARY:

No hits found.
Lines analyzed = 11 in approximately 0.02 seconds (663 lines/second)
Physical Source Lines of Code (SLOC) = 10
Hits@level = [0]   1 [1]   0 [2]   0 [3]   0 [4]   0 [5]   0
Hits@level+ = [0+]   1 [1+]   0 [2+]   0 [3+]   0 [4+]   0 [5+]   0
Hits/KSLOC@level+ = [0+] 100 [1+]   0 [2+]   0 [3+]   0 [4+]   0 [5+]   0
Minimum risk level = 1
```
