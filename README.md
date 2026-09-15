## sebottt

Developer and student. I build web applications and then run them myself, which is how I ended up
spending as much time on servers, certificates and authentication as on the code.

Most of what I know came from maintaining one application in production. Writing it taught me PHP and
JavaScript. Keeping it online taught me Apache, MySQL, certificate renewal, SSH key handling, and why
a backup file left in the web root is a problem.

### Selected work

**[firefox-default-search-anthropic](https://github.com/sebottt/firefox-default-search-anthropic)**
Analysis of a Firefox extension, signed and distributed by Mozilla, that shipped a malicious payload
through an automatic update twelve days after a clean install. I reverse-engineered the
command-and-control channel, recovered the configuration the operator had pushed to my browser, and
reconstructed the timeline from the profile's SQLite artefacts. Includes the sample, hashes and
indicators. No prior public write-up of this behaviour existed.

**[Veredict_App](https://github.com/sebottt/Veredict_App)**
Institutional web platform for students, teachers and administrators. PHP without a framework, vanilla
JavaScript, MySQL. JWT in an httpOnly cookie with server-side role guards, Microsoft OAuth for single
sign-on, deployed on AWS behind Apache with TLS. I also administer the server it runs on.

**[confession-relay-bot](https://github.com/sebottt/confession-relay-bot)**
Python relay bot running under systemd on the same infrastructure.

### Stack

**Languages**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Web**

![Vanilla JS](https://img.shields.io/badge/Vanilla%20JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node](https://img.shields.io/badge/Node-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![Composer](https://img.shields.io/badge/Composer-885630?style=flat-square&logo=composer&logoColor=white)

**Data**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black)

**Infrastructure**

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-232F3E?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-303030?style=flat-square)
![Certbot](https://img.shields.io/badge/Certbot-003A70?style=flat-square&logo=letsencrypt&logoColor=white)
![fail2ban](https://img.shields.io/badge/fail2ban-303030?style=flat-square)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Currently

Moving toward security work, from the practical side: host hardening, log analysis, and malware
analysis. More interested in how systems fail in production than in how they are supposed to behave.
