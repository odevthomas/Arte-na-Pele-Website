![Home](https://github.com/user-attachments/assets/fc4365b4-1cd7-4f8c-97c7-e50d662e3bf7)
# Arte na Pele Studios

Landing page profissional para o estúdio de tatuagem **Arte na Pele Studios**. O projeto foi desenvolvido utilizando **React**, **TypeScript** e **Vite** para proporcionar uma experiência rápida e moderna para os usuários.

## 🚀 Tecnologias Utilizadas

- **React** + **Vite** → Estrutura rápida e eficiente para desenvolvimento
- **TypeScript** → Tipagem estática para maior segurança no código
- **Styled Components** → Estilização modular e dinâmica
- **React Router** → Navegação entre páginas
- **Framer Motion** → Animações suaves e interativas

## 📌 Funcionalidades

- Apresentação profissional do estúdio e seus serviços
- Galeria de tatuagens realizadas
- Seção de artistas e seus estilos de especialização
- Formulário de agendamento online
- Depoimentos de clientes
- Seção de perguntas frequentes (FAQ)

## 📷 Layout e Design

O design foi pensado para refletir a identidade visual de um estúdio de tatuagem, com elementos visuais impactantes, tipografia forte e cores marcantes.

## 🎨 Estrutura de Pastas

```
📂 arte-na-pele-studios
 ┣ 📂 src
 ┃ ┣ 📂 assets → Imagens e ícones
 ┃ ┣ 📂 components → Componentes reutilizáveis
 ┃ ┣ 📂 pages → Páginas principais (Home, Galeria, Artistas, Contato...)
 ┃ ┣ 📂 styles → Estilos globais e temáticos
 ┃ ┗ 📜 main.tsx → Arquivo principal do React
 ┣ 📜 package.json → Dependências e scripts
 ┣ 📜 tsconfig.json → Configuração do TypeScript
 ┗ 📜 README.md → Este documento
```

## 🔧 Como Executar o Projeto

1. **Clone o repositório**
   ```sh
   git clone https://github.com/seu-usuario/arte-na-pele-studios.git
   ```

2. **Acesse a pasta do projeto**
   ```sh
   cd arte-na-pele-studios
   ```

3. **Instale as dependências**
   ```sh
   npm install
   # ou
   yarn install
   ```

4. **Inicie o servidor de desenvolvimento**
   ```sh
   npm run dev
   # ou
   yarn dev
   ```

5. **Acesse no navegador**
   ```
   http://localhost:5173
   ```

## 📌 Expansão e Personalização

Para personalizar o ESLint e aprimorar a configuração do TypeScript, recomendamos:

- Adicionar `plugin:@typescript-eslint/recommended-type-checked`
- Utilizar `plugin:react/recommended` para melhor suporte ao React
- Atualizar `parserOptions` no `.eslintrc.js`:

```js
export default {
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

## 📞 Contato

Caso tenha dúvidas ou queira contribuir, entre em contato:
- **E-mail:** contato@artenapele.com.br
- **Instagram:** [@artenapelestudios](https://instagram.com/artenapelestudios)

📌 Desenvolvido por **@odevthoma** | © 2025 Arte na Pele Studios
