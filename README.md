# Devedor Tranquilão 🕶️💸

Landing Page humorística com estética **Vaporwave / Cyberpunk**, vendendo um suposto curso de como "Dever com Estilo" e dominar a arte da dívida legal.

## 🔗 Acesso ao Projeto
O projeto foi publicado ("deploy") utilizando a plataforma Vercel. 
Você pode acessá-lo através do link abaixo:

👉 **[https://devedor-tranquilao.vercel.app/](https://devedor-tranquilao.vercel.app/)**

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando os fundamentos da web (Vanilla), sem o uso de frameworks complexos, demonstrando habilidades essenciais em Front-end:

- **HTML5:** Estruturação semântica do conteúdo, dividida em seções como Hero Section, Módulos e CTA (Call to Action).
- **CSS3 (Vanilla):** 
  - Estilização completa e responsiva.
  - Uso de **Variáveis CSS Root** para padronização de paleta de cores (roxo neon, amarelo vivo, etc).
  - Animações CSS com `@keyframes` para criar o "Vaporwave Grid Background" com perspectiva 3D em movimento continuo.
  - Flexbox e CSS Grid para o alinhamento centralizado e sistema de cards.
- **JavaScript (Vanilla):**
  - **Typing Effect:** Um script que digita e apaga frases diferentes simulando uma máquina de escrever na Hero Section.
  - **Fake Countdown Timer:** Um temporizador que diminui regressivamente para gerar o gatilho mental de "escassez" instigando o usuário à compra.
  - Prevenção de envio de formulários irreais e exibição de alertas engraçados na interação de Call to Action.

## 📖 Como foi o processo de desenvolvimento?

1. **Estrutura (HTML):** Criação das seções principais (`<header>`, `.hero`, `.modules`, `.cta-section`).
2. **Estética (CSS):** Aplicação das cores Cyberpunk/Vaporwave. Criação do fundo animado em grid 3D (`perspective` + `transform: rotateX`), adição de "text-shadows" e "box-shadows" para o efeito luminoso ou "glitch".
3. **Interatividade (JS):** Lógica simples e eficaz utilizando `setInterval` e `setTimeout` para gerenciar a passagem do tempo do timer regressivo e controlar o índice de caracteres no efeito de digitação do subtítulo.
4. **Deploy:** Lançamento público através da infraestrutura da **Vercel**, conectando ou enviando diretamente o diretório final.