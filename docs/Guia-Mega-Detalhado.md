
## 🚀 Quick Start (5 minutos)

### Pré-requisitos
- Node.js 18.x
- Python 3.9+
- Docker Desktop
- Git

### Instalação Local

```bash
# 1. Clonar repositório
git clone https://github.com/vinicius898/outletia-complete.git
cd outletia-complete

# 2. Setup Backend
cd backend
npm install
cp .env.example .env
docker-compose up -d
npm run dev

# 3. Em outro terminal, Setup Frontend
cd frontend
npm install
cp .env.example .env
npm start

# 4. Abrir no navegador
# Frontend: http://localhost:3000
# Backend: http://localhost:3001
