# Cyber Attack Simulation Platform 

A sandboxed web application designed to demonstrate how common cyber attacks work (phishing, web vulnerabilities, API flaws) in a safe and controlled environment. 

## Objective 

This project simulates real-world attack scenarios without performing actual exploitation. It is built for: 
 - CyberSecurity education
 - Secure coding awareness 
 - Application Security (AppSec) practice 

----- 
## Key Features 
- Phishing attack simulation (email -> fake login -> result) 
- Web vulnerabilities (SQL injection, XSS, CSRF)
- API Security flaws (BOLA, token misuse) 
- Authentication & session security demos 
- Attack vs Secure mode comparison 
- Logging and detection dashboard (planned) 

------ 

## Core Concept 

The application follows a dual-mode architecture. 
- ** Vulnerable Mode ** -> intentionally insecure implementation. 
- ** Secure Mode ** -> properly fixed implementation. 

Example: 
- /api/vuln/login -> SQL injection possible 
- /api/secure/login -> parameterized queries 

------ 
## Tech Stack 

Frontend:
- Next
- Tailwind CSS 
- Framer Motion 

Backend: 
- Next.js API Routes 

Database: 
- PostgreSQL (planned)

Other: 
- JWT Authentication 
- Docker (planned) 

-------- 

## Project structure 

src/ 
├── app/ 
│ ├── api/ 
│ │ ├── vuln/ 
│ │ └── secure/ 
│ ├── phishing/ 
│ ├── vulnerabilities/ 
│ ├── components/ 
├── lib/

---- 

## Safety and Ethical Use 

This project is strictly designed for educational purpose only. 
- No real phishing emails are sent. 
- No real credentials are stored. 
- All attacks are simulated within a sandbox. 
- Sensitive inputs are masked or discarded. 

------- 
## Getting Started 

'''
git clone git@github.com:udayydogra/cyber-attack-simulator.git
cd cyber-attack-simulator
npm install 
npm run dev 
'''
---- 

## Roadmap 
- [ ] Phishing simulation module
- [ ] SQL Injection demo
- [ ] XSS demo
- [ ] Authentication flaws
- [ ] API security module
- [ ] Logging dashboard
- [ ] Threat modeling section

------- 

## Why This Project 

 This Project is focused on understanding both: 
- How vulnerabilities are exploited. 
- How they should be properly fixed. 

It is intended as a hands-on learning platform for Application Security. 

---- 
### Disclaimer 

This tool must not be used for real-world attacks or unauthorized testing. 
Ass demonstrations are limited to controlled environments. 
