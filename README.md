Crie um projeto completo para GitHub de um site moderno de Inteligência Artificial com interface Drag & Drop.

Objetivo:
Permitir que o usuário arraste e solte arquivos, imagens, textos ou documentos em uma área específica. Após o envio, a aplicação deve utilizar uma API de IA (OpenAI ou compatível) para analisar o conteúdo e gerar respostas inteligentes.

Tecnologias:
- React + Vite
- Tailwind CSS
- JavaScript (ou TypeScript)
- Node.js + Express para o backend
- Axios para chamadas à API
- React Router
- ESLint
- Estrutura preparada para banco de dados futuramente

Funcionalidades:
- Área Drag & Drop com animações.
- Upload de PDF, DOCX, TXT, PNG, JPG e JPEG.
- Visualização do arquivo enviado.
- Barra de progresso durante o upload.
- Integração com API da OpenAI.
- IA capaz de:
  - resumir documentos;
  - explicar conteúdos;
  - traduzir textos;
  - responder perguntas;
  - gerar descrições;
  - classificar documentos.
- Histórico das análises.
- Campo para fazer perguntas adicionais sobre o mesmo arquivo.
- Botão para copiar resultado.
- Botão para baixar resultado em TXT ou PDF.
- Modo claro e escuro.
- Interface totalmente responsiva.
- Mensagens de erro amigáveis.
- Loading animado enquanto a IA processa.

Interface:
- Design minimalista.
- Paleta moderna.
- Ícones do Lucide React.
- Animações com Framer Motion.
- Componentes reutilizáveis.
- Layout semelhante aos sites ChatGPT, Claude e Gemini.

Estrutura do projeto:

/
├── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   ├── assets/
│   └── App.jsx
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── services/
│   ├── uploads/
│   └── server.js
├── README.md
├── .env.example
├── package.json
└── .gitignore

O README deve conter:
- descrição do projeto;
- tecnologias utilizadas;
- instalação;
- configuração da variável OPENAI_API_KEY;
- execução do frontend;
- execução do backend;
- deploy no Vercel e Render;
- licença MIT.

Crie também:
- arquivo .gitignore adequado;
- arquivo .env.example;
- comentários no código explicando as principais funções;
- código limpo seguindo boas práticas;
- arquitetura preparada para autenticação JWT e banco PostgreSQL no futuro.

O projeto deve estar pronto para ser enviado diretamente ao GitHub e executado após instalar as dependências com npm install.
