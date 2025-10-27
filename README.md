🏫 Projeto Escola Noturna — Sistema de Gestão Escolar

Escola Noturna é uma aplicação web desenvolvida em Node.js + Express (MVC) para modernizar a gestão acadêmica de escolas e cursos noturnos.
O sistema oferece uma interface intuitiva e responsiva para cadastro e acompanhamento de alunos, turmas, notas e frequência — com relatórios visuais e painéis administrativos em tempo real.

✨ Principais Funcionalidades

👩‍🏫 Cadastro de alunos e turmas com avatares automáticos e interface moderna.

📝 Lançamento de notas e frequência de forma rápida, com validação automática.

📊 Dashboard com KPIs (alunos ativos, turmas, média geral, frequência média, alunos em risco).

📈 Relatórios e gráficos interativos (Chart.js) com visão geral por turma.

🧭 Filtro e busca instantânea na lista de alunos.

🚨 Destaque automático para alunos com nota abaixo de 6 ou frequência abaixo de 75%.

🗂️ Exportação de dados em CSV (importação futura planejada).

🌙 Modo escuro/claro com toggle dinâmico.

📦 Estrutura MVC organizada, fácil de manter e evoluir.

🧰 Tecnologias Utilizadas

Backend: Node.js + Express

Frontend: EJS, Bootstrap 5, Chart.js

Banco de Dados: Arquivo JSON (com seed automático de turmas A, B e C)

Outros: Multer, UUID, layout responsivo, persistência local

🚀 Próximos Passos (Roadmap)

📚 Perfis de acesso (professor, secretaria, aluno)

🏫 Controle de disciplinas, avaliações e aulas

📅 Calendário de presença e relatórios detalhados por aluno

☁️ Deploy em nuvem (Render ou Railway) com persistência

🐘 Integração com banco PostgreSQL

🧑‍💻 Como Rodar Localmente
git clone https://github.com/SEU_USUARIO/escola-noturna-mvc.git
cd escola-noturna-mvc
npm install
npm start


Acesse: http://localhost:3000

💡 Dica: se quiser recomeçar com as turmas padrão (A/B/C), apague data/db.json antes de rodar.
