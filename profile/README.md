# 🧠 LivreMente

Sistema web para acompanhamento de crises de enxaqueca, desenvolvido para ajudar pacientes a monitorar, analisar e entender melhor seus padrões de dor de cabeça.

## 📋 Sobre o Projeto

O **LivreMente** é uma aplicação completa que permite aos usuários:

- ✅ Registrar crises de enxaqueca com detalhes completos (data, hora, intensidade, sintomas, gatilhos, medicação)
- 📊 Visualizar histórico completo de crises
- 📈 Gerar gráficos e relatórios analíticos
- 📄 Exportar relatórios em PDF
- 🔍 Filtrar e buscar crises por período
- ✏️ Editar e excluir registros

## 🏗️ Arquitetura

O projeto é dividido em duas partes principais:

### Frontend
- **Framework**: Vue 3 com Composition API
- **Build Tool**: Vite
- **Roteamento**: Vue Router
- **Estado**: Pinia
- **HTTP Client**: Axios
- **Estilização**: TailwindCSS
- **Gráficos**: Chart.js
- **PDF**: jsPDF

### Backend
- **Framework**: Lumen 10 (Laravel Micro-framework)
- **PHP**: 8.4
- **Autenticação**: Laravel Sanctum (a ser implementado)
- **Banco de Dados**: SQLite/MySQL/PostgreSQL

## 🚀 Tecnologias

### Frontend
- Vue 3
- Vite
- Vue Router
- Pinia
- Axios
- TailwindCSS
- Chart.js
- jsPDF

### Backend
- Lumen 10
- PHP 8.4
- Laravel Sanctum
- Eloquent ORM

## 📁 Estrutura do Projeto

```
LivreMente/
├── frontend/          # Aplicação Vue.js
│   ├── src/
│   │   ├── components/   # Componentes reutilizáveis
│   │   ├── views/        # Páginas da aplicação
│   │   ├── stores/       # Gerenciamento de estado (Pinia)
│   │   ├── composables/  # Composables Vue
│   │   ├── router/       # Configuração de rotas
│   │   └── ...
│   └── package.json
│
└── backend/          # API Lumen
    ├── app/
    │   ├── Http/
    │   │   └── Controllers/  # Controladores da API
    │   ├── Models/           # Modelos Eloquent
    │   └── ...
    ├── routes/               # Rotas da API
    ├── database/             # Migrations e Seeders
    └── composer.json
```

## 🛠️ Instalação e Configuração

### Pré-requisitos

- Node.js 18+ (para o frontend)
- PHP 8.4+ (para o backend)
- Composer (para o backend)
- Banco de dados (SQLite, MySQL ou PostgreSQL)

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

## 📝 Funcionalidades

### Autenticação
- Login e registro de usuários
- Proteção de rotas
- Gerenciamento de sessão

### Registro de Crises
- Data e hora da crise
- Intensidade (1-10)
- Sintomas (pré-definidos e personalizados)
- Gatilhos (pré-definidos e personalizados)
- Medicação utilizada

### Histórico e Análises
- Visualização de todas as crises registradas
- Filtros por data
- Gráficos de intensidade ao longo do tempo
- Análise de sintomas mais frequentes
- Análise de gatilhos mais comuns
- Distribuição de crises por dia da semana
- Filtros mensais e anuais

### Relatórios
- Geração de PDF com dados filtrados
- Estatísticas detalhadas
- Visualização de padrões

## 🎨 Design

O sistema possui um design limpo e minimalista, com:
- Tema claro/escuro
- Cores suaves focadas em bem-estar
- Cor principal: Laranja
- Interface responsiva (mobile-first)
- Experiência de usuário intuitiva

## 📱 Responsividade

A aplicação é totalmente responsiva e funciona perfeitamente em:
- 📱 Dispositivos móveis
- 💻 Tablets
- 🖥️ Desktops

## 🔐 Segurança

- Autenticação via tokens
- Validação de dados
- Proteção CSRF
- Sanitização de inputs

## 🧪 Testes

### Frontend
```bash
cd frontend
npm run test
```

### Backend
```bash
cd backend
php artisan test
```

## 📚 Documentação

- [Documentação do Frontend](./frontend/README.md)
- [Documentação do Backend](./backend/README.md)

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## 👤 Autor

**Gabriel Domiciano**
- Email: gabriel.ads18@gmail.com

## 🙏 Agradecimentos

Agradecimentos a todos que contribuíram para este projeto.

---

Desenvolvido com ❤️ para ajudar pessoas a entenderem melhor suas crises de enxaqueca.

