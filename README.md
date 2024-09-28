<h1 align="center">Vulnerable Box Resources</h1>

<p align="center">
    <strong> Live Application](https://vulnerable-box-resources.infosecwarrior.com/)</strong>
</p>

**Vulnerable Box Resources** is a curated collection of scan outputs and data designed to help you analyze and exploit vulnerable machines. This repository provides detailed insights into the inner workings of your target systems, making it easier to identify potential security gaps, weaknesses, and attack vectors.

## Features

- **Nmap Port Scanning**: Gain detailed insights into open ports, running services, and potential security weaknesses on the target machine.

- **Directory Bruteforcing**: Uncover hidden directories and files on web servers using tools like `dirsearch`, revealing potential entry points and misconfigurations.

- **Web Technology Identification**: Identify technologies used by the target website using tools like `whatweb`.

- **Vulnerability Scanners**: Scanning results from tools like `nikto` and `nuclei` to identify known vulnerabilities, misconfigurations, and security flaws in web applications.

## How to Submit Your Target Machine Data

To contribute your scan data to this repository, please follow the steps below:

1. **Run the Scanning Script**: First, visit the repository [Box Scanning Script](https://github.com/infoSecWarrior/Offensive-Pentesting-Scripts/tree/main/Box-Scann), which provides the necessary script along with installation instructions.

2. **Install and Execute the Script**: After downloading and setting up the script, run it using the following command, replacing `<target_ip>` with your target machine's IP address and `<output_directory_prefix>` with your desired filename prefix:

    ```bash
    # python box-scan.py -t <target_ip> -o <output_directory_prefix>
    ```

3. **Complete the Scanning**: Once the script finishes scanning, follow these steps to submit your results:

   - **Fork the Repository**: Create a fork of the Vulnerable Box Resources repository to your GitHub account.
   
   - **Create a New Directory**: Inside your fork, create a new directory named after the target machine (e.g., `Machine-Name`).
   
   - **Upload Scanning Outputs**: Upload the output files generated by the script into the newly created directory.

4. **Get the Raw Link of Your Nmap Scan File**:

   - Navigate to your directory and copy the **Raw link** of your `{output_directory_prefix}-nmap-scan-output.xml` file.
   - Example link format:  
     `https://raw.githubusercontent.com/your-github-username/Vulnerable-Box-Resources/main/Machine-Name/output_directory_prefix-nmap-scan-output.xml`
     
5. **Modify the Username in the URL**:

   - Change `your-github-username` to `infoSecWarrior` in the raw link.  
     For example,  
     `https://raw.githubusercontent.com/infoSecWarrior/Vulnerable-Box-Resources/main/Machine-Name/output_directory_prefix-nmap-scan-output.xml`

6. **Update the Raw-File-Links.txt File**:

   - Edit the `Raw-File-Links.txt` file in the repository and insert the modified URL of your Nmap scan file.

7. **Create a Pull Request**:

	- Once you’ve made all the changes, go to your forked repository, click on "Pull requests," and select "New pull request."
