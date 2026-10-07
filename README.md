# 🧠 Dev Quiz (Quiz de Programação)

Quiz interativo para testar seus conhecimentos em programação web. O usuário escolhe uma categoria, responde a uma sequência de perguntas de múltipla escolha e, no final, vê sua pontuação.

Desenvolvido com **React** e **Vite**.

## ✨ Funcionalidades

- **Escolha de categoria**: as perguntas são referentes a uma das linguagens *HTML*, *CSS* ou *JavaScript*.
- **Perguntas de múltipla escolha** com contador de progresso ("Pergunta 2 de 5").
- **Feedback imediato**: a alternativa correta é destacada em verde depois da resposta.
- **Ajudas durante o quiz**: botão **Excluir uma**, para eliminar uma alternativa, e dicas para ajudar a responder.
- **Botão Continuar** para avançar para a próxima pergunta.
- **Tela de resultado** ("Fim de Jogo!") com a pontuação e o número de acertos.
- **Botão Reiniciar** para jogar novamente.

## 🎬 Demonstração

https://github.com/user-attachments/assets/837e048f-96ba-4229-b24d-6bdf366bb624

## 🛠️ Tecnologias

- **[React 19](https://react.dev/)** — construção da interface
- **[Vite](https://vite.dev/)** — ambiente de desenvolvimento e build
- **[ESLint](https://eslint.org/)** — padronização e qualidade do código
- **CSS** — estilização

## 📁 Estrutura do projeto

```
Dev-Quiz/
├── public/            # Arquivos estáticos
├── src/               # Código-fonte da aplicação (React)
├── index.html         # Página HTML principal
├── vite.config.js     # Configuração do Vite
├── eslint.config.js   # Configuração do ESLint
└── package.json       # Dependências e scripts
```

## 🚀 Como executar

**Pré-requisito:** [Node.js](https://nodejs.org/) (versão LTS recente) e npm.

1. Clone o repositório:

   ```bash
   git clone https://github.com/jotapefp/Dev-Quiz.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd Dev-Quiz
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Abra o endereço exibido no terminal (geralmente `http://localhost:5173`).

### Outros scripts

| Comando           | Descrição                                   |
| ----------------- | ------------------------------------------- |
| `npm run dev`     | Inicia o servidor de desenvolvimento        |
| `npm run build`   | Gera a versão de produção                   |
| `npm run preview` | Visualiza localmente a versão de produção   |
| `npm run lint`    | Verifica o código com o ESLint              |

## 🧭 Como usar

1. Na tela inicial, escolha a categoria: **HTML**, **CSS** ou **JavaScript**.
2. Leia a pergunta e clique na alternativa que você considera correta.
3. Se precisar de ajuda, use **Excluir uma** para eliminar uma alternativa ou consulte a dica.
4. Clique em **Continuar** para ir para a próxima pergunta.
5. No final, confira sua **pontuação** e clique em **Reiniciar** para jogar de novo.

## 👤 Autor

**João Paulo Pinheiro Ferraz de Arruda**

- GitHub: [@jotapefp](https://github.com/jotapefp)
- LinkedIn: [joao-paulo-pinheiro-ferraz-de-arruda](https://www.linkedin.com/in/joao-paulo-pinheiro-ferraz-de-arruda)
