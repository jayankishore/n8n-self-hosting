# n8n-self-hosting
n8n is an open-source workflow automation tool. In this project, n8n was self-hosted locally using two methods: npm installation with Node.js and Docker container deployment. Both setups successfully launched the n8n editor at http://localhost:5678 for automation workflow creation.


## Method 1: npm Installation

1. Install Node.js (v20 recommended)
2. Run:

```bash
npm install n8n
npx n8n start

	3.	Open: http://localhost:5678

⸻

Method 2: Docker Installation
	1.	Install Docker Desktop
	2.	Run:

docker run -it --rm -p 5678:5678 n8nio/n8n

	3.	Open: http://localhost:5678

---

# ✅ Final Suggestion

✔ Content is compulsory  
✔ Screenshots are optional but give extra marks


