# Hi, I'm Harry 👋

Application Development & Delivery student at **Red River College Polytechnic** in Winnipeg, MB. I build backend APIs, data pipelines, and cloud-deployed apps, and I enjoy integrating local LLMs into real workflows.

- 🎓 Diploma, Application Development & Delivery (May 2025 – May 2027) · GPA 4.5
- 🔭 Latest project: [Text Summary API](https://github.com/sudepolar/Text-Summary-API)
- 🌱 Growing in: Full-stack Development
- 💼 Looking for: a **Winter 2027 Jr. Developer co-op**
- 📫 Reach me: emnacenharry@gmail.com

---

## 🚀 Featured Project

### [Text Summary API](https://github.com/sudepolar/Text-Summary-API)

A REST API that summarizes uploaded `.txt`, `.pdf`, and `.docx` files (or raw text) using **Llama 3.1 (8B)** running locally on **Ollama**, with no third-party AI service.

```
Client ──► Node.js / Express API ──► Python / FastAPI LLM service ──► Ollama (llama3.1:8b)
              │
              └──► Firebase Auth + Firestore
```

- Two-service design: a TypeScript/Express API in front of a Python/FastAPI LLM service
- Firebase Auth with role-based access control (`admin` / `user`) through custom claims
- File text extraction with `pdf-parse` and `mammoth`, request validation with Joi
- Jest + Supertest tests with mocked Firebase and LLM clients
- GitHub Actions for tests, ESLint linting, and a supply-chain security scan
- Interactive Swagger UI and Redoc API documentation

<p align="left">
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="30" height="30"/></a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" alt="Express" title="Express" width="30" height="30"/></a> <a href="https://fastapi.tiangolo.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" width="30" height="30"/></a> <a href="https://ollama.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/ollama/ollama/main/docs/ollama.png" alt="Ollama" title="Ollama" width="30" height="30"/></a> <a href="https://firebase.google.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-original.svg" alt="Firebase" title="Firebase" width="30" height="30"/></a> <a href="https://jestjs.io" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jest/jest-plain.svg" alt="Jest" title="Jest" width="30" height="30"/></a> <a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" title="GitHub Actions" width="30" height="30"/></a>
</p>

---


## 🧰 Tech Stack

**Languages**

<p align="left">
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="40" height="40"/></a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="40" height="40"/></a> <a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40"/></a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" width="40" height="40"/></a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" width="40" height="40"/></a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" alt="Bash" title="Bash" width="40" height="40"/></a>
</p>

**Back-End & APIs**

<p align="left">
<a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" width="40" height="40"/></a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" alt="Express" title="Express" width="40" height="40"/></a> <a href="https://fastapi.tiangolo.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" width="40" height="40"/></a> <a href="https://swagger.io" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swagger/swagger-original.svg" alt="Swagger" title="Swagger" width="40" height="40"/></a>
</p>

**Front-End**

<p align="left">
<a href="https://react.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" title="React" width="40" height="40"/></a> <a href="https://vitejs.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vitejs/vitejs-original.svg" alt="Vite" title="Vite" width="40" height="40"/></a> <a href="https://tailwindcss.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" title="Tailwind CSS" width="40" height="40"/></a>
</p>

**Data & AI**

<p align="left">
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40"/></a> <a href="https://firebase.google.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-original.svg" alt="Firebase" title="Firebase" width="40" height="40"/></a> <a href="https://aws.amazon.com/dynamodb/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dynamodb/dynamodb-original.svg" alt="DynamoDB" title="DynamoDB" width="40" height="40"/></a> <a href="https://pandas.pydata.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="Pandas" title="Pandas" width="40" height="40"/></a> <a href="https://ollama.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/ollama/ollama/main/docs/ollama.png" alt="Ollama" title="Ollama" width="40" height="40"/></a>
</p>

**Cloud & DevOps**

<p align="left">
<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" title="AWS" width="40" height="40"/></a> <a href="https://www.docker.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="40" height="40"/></a> <a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" title="GitHub Actions" width="40" height="40"/></a> <a href="https://git-scm.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" title="Git" width="40" height="40"/></a> <a href="https://www.linux.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" title="Linux" width="40" height="40"/></a> <a href="https://www.vagrantup.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vagrant/vagrant-original.svg" alt="Vagrant" title="Vagrant" width="40" height="40"/></a> <a href="https://jestjs.io" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jest/jest-plain.svg" alt="Jest" title="Jest" width="40" height="40"/></a>
</p>

---

## 🤝 Connect

<p align="left">
<a href="https://linkedin.com/in/harry-emnacen" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="LinkedIn" title="LinkedIn" width="40" height="40"/></a>
</p>

📫 [emnacenharry@gmail.com](mailto:emnacenharry@gmail.com)
