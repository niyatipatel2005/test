## Excalibur_Hackathon

## Deep Domain Analyzer

A comprehensive tool to trace the true origin of websites and uncover potential security threats.

## Description

Deep Domain Analyzer is an advanced web application designed to help users identify the true origin of websites, particularly those utilizing Content Delivery Networks (CDNs) like Cloudflare. With cyber threats becoming increasingly sophisticated, this tool provides a robust solution for analyzing domain information and revealing hidden details about potentially suspicious sites.

### Core Features:

1. Malicious Website Detection: Analyzes DNS records, network behavior, and website patterns to classify potential threats and malicious activities.
2. DNS Resolution: Resolves domain names to IP addresses to identify the hosting infrastructure and location of websites.
3. VirusTotal Integration: Leverages the VirusTotal API to cross-check domains against known malicious threat databases, ensuring a more comprehensive security analysis.
4. Geolocation & Metadata Retrieval: Uses IPinfo to extract detailed geolocation data, ASN, and ISP information, providing crucial context about the domain's hosting environment.
5. Subdomain Discovery (Sublist3r): Discovers associated subdomains, revealing additional entry points and expanding the scope of the investigation and also detects likely origin servers.
6. IP Range Comparison: Cross-references the IPs of discovered subdomains against known CDN ranges (Cloudflare, AWS, Azure) to help pinpoint potential origin servers behind the CDN layer.
7. WHOIS & Certificate Analysis: Retrieves domain registration data and examines SSL/TLS certificates for further verification, adding another layer of transparency to the investigative process.


## Built With



### Programming Languages:

* [![Python][Python]][Python-url] – Backend processing and API integrations
* [![JavaScript][JavaScript]][JavaScript-url] – Frontend interactivity and API calls
* [![HTML5][HTML5]][HTML5-url] – UI design and styling
* [![CSS3][CSS3]][CSS3-url] – UI design and styling


### Frameworks & Libraries:

* [![Flask][Flask]][Flask-url] – For building a web-based application
* [![Sublist3r][Sublist3r]][Sublist3r-url] – For subdomain enumeration


### APIs & Tools:

* [![IPinfo][IPinfo]][IPinfo-url] – For gathering IP address information
* [![VirusTotal][VirusTotal]][VirusTotal-url] – For gathering security threat intelligence


   
## Getting Started

### Prerequisites

Before installing and running the program, ensure you have the following:

* **Python 3.10.0** installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).
* **Git** installed to clone the repository. If you don't have it, download it from [git-scm.com](https://git-scm.com/).
* Operating System: **Windows** or **Linux**.

### Installing

1. **Clone the Repository:**

   Start by cloning the project repository to your local machine. The --recursive flag ensures that if your repository contains any submodules (like Sublist3r), they will be cloned as well. Open your terminal or command prompt and run the following command:
   ```bash
   git clone --recursive https://github.com/SuhaniPatel88/Vertex_Hackathon_2025
   cd Exaclibur_Hackathon_2025
   ```
   

2. **Install the Requirements:**

   The project has a `requirements.txt` file that lists all the necessary dependencies. To install them, run:
   ```bash
   pip install -r requirements.txt
   ```

   This will install all the required Python libraries.

### Executing Program

1. **Running the Application:**

   Once you have cloned the repository and installed the requirements, you can start the application. In the project directory, run the following command:
   ```bash
   python app.py
   ```

2. **Accessing the Application:**

   After running `app.py`, the app will start a local server. Open your web browser and go to:
   ```
   http://127.0.0.1:5000
   ```

3. **Entering the Domain:**

   On the homepage, you will be prompted to enter a domain name. Please **do not include** `http://` or `https://`. For example, you should enter:
   ```
   example.com
   ```
   After entering the domain, press **Submit**.

4. **View Results:**

   The app will process the request and display the result. If there is a technical issue and the result shows up empty, you can **restart the process** by entering the domain again and submitting.





## Authors

* Niyati Patel
* Suhani Patel
* Nishant Kumar



## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.

[Python]: https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white
[Python-url]: https://www.python.org/

[JavaScript]: https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black
[JavaScript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript

[HTML5]: https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white
[HTML5-url]: https://developer.mozilla.org/en-US/docs/Web/HTML

[CSS3]: https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white
[CSS3-url]: https://developer.mozilla.org/en-US/docs/Web/CSS

[Flask]: https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white
[Flask-url]: https://flask.palletsprojects.com/

[Sublist3r]: https://img.shields.io/badge/Sublist3r-FF6F00?style=flat&logo=python&logoColor=white
[Sublist3r-url]: https://github.com/aboul3la/Sublist3r

[IPinfo]: https://img.shields.io/badge/IPinfo-000000?style=flat&logo=ipinfo&logoColor=white
[IPinfo-url]: https://ipinfo.io/

[VirusTotal]: https://img.shields.io/badge/VirusTotal-FF6F00?style=flat&logo=virustotal&logoColor=white
[VirusTotal-url]: https://www.virustotal.com/
