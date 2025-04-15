
---

### 🖥️ **Frontend** (`frontend/README.md`)

```markdown
# 🎨 Aplicação Frontend

Interface React para o sistema de gerenciamento de tarefas

## 📦 Como Construir
```bash
docker build -t seuusuario/tarefas-frontend:1.0.0 .

docker run -d \
  -p 3000:3000 \
  -e REACT_APP_API_URL=http://localhost:5000 \
  --name frontend \
  seuusuario/tarefas-frontend:1.0.0