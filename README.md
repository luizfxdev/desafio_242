🧙‍♂️ Reino dos JSONs - Aventura Interativa


Uma experiência imersiva e mágica para resolver o desafio de navegação em estruturas JSON complexas, envolvida em efeitos visuais modernos e animações.

🧙‍♂️ Reino dos JSONs - Aventura Interativa
Uma experiência imersiva e mágica para resolver o desafio de navegação em estruturas JSON complexas, envolvida em efeitos visuais modernos e animações cinematográficas.
Mostrar Imagem
Mostrar Imagem
Mostrar Imagem
🎯 Sobre o Projeto
O Reino dos JSONs é uma aplicação web interativa que transforma um desafio técnico de programação em uma aventura mágica. O usuário deve navegar através de uma estrutura JSON complexa para encontrar um valor secreto escondido, tudo isso em um ambiente visualmente impressionante com:

✨ Animações fluidas e efeitos de partículas
🎬 Background de vídeo personalizável
🌟 Interface moderna com glassmorphism
📱 Design responsivo
🎮 Experiência gamificada

🔍 O Desafio
Objetivo: Extrair a string "Eureka! Você encontrou!" da seguinte estrutura JSON:
json{
  "portal": {
    "camada": [
      null,
      {
        "mistério": [
          "perdido",
          {
            "pista": "continue procurando",
            "chave": {
              "caixa": [
                "não aqui",
                {
                  "deep": "mais profundo",
                  "segredo": "Eureka! Você encontrou!"
                }
              ]
            }
          }
        ]
      },
      "confuso"
    ]
  }
}
Solução: json.portal.camada[1].mistério[1].chave.caixa[1].segredo
🚀 Funcionalidades
🎨 Visuais e Animações

Partículas flutuantes douradas com movimento contínuo
Estrelas cintilantes no fundo
Efeitos de glassmorphism nos containers
Animações de pulsação e brilho em tempo real
Transformações 3D nos botões com feedback visual

🎬 Background Customizável

Suporte a vídeo MP4 como background
Fallback para gradiente se o vídeo não carregar
Overlay ajustável para legibilidade do texto

🎮 Interatividade

Animação de digitação para exibir o JSON
Revelação do caminho secreto com destaque visual
Sistema de progresso com 4 etapas visuais
Feedback háptico em dispositivos compatíveis
Efeitos de celebração ao resolver o enigma

📱 Responsividade

Layout adaptável para desktop e mobile
Elementos ocultos automaticamente em telas pequenas
Texto com quebra automática para melhor legibilidade

🛠️ Tecnologias Utilizadas

HTML5: Estrutura semântica e elementos modernos
CSS3: Animações, gradientes, transforms 3D, glassmorphism
JavaScript ES6+: Lógica interativa e manipulação do DOM
Google Fonts: Tipografia elegante (Cinzel + Roboto Mono)

📋 Recursos Utilizados

CSS Grid e Flexbox
CSS Animations e Transforms
ES6+ JavaScript
HTML5 Video
Vibration API (opcional)
