# O que é Omnisender?
Omnisender é uma aplicação feita em Node.jsque utiliza envio para plataformas do Discord e WhatsApp simultaneamente.
O objetivo do projeto é facilitar o envio da mesma mensagem em canais diferentes, de forma gratuita, sem que você precise pagar para utilizar uma função simples.
No modelo atual possuí já as funções basicas de envio e formatação de texto para ambas aplicações.
Como é um projeto para Self Hosted você pode installar tanto em Windows como Linux, de forma simples, fácil e descomplicada.

# OmniSender OpenSource v1.0.0

## Na v1.0.0 já conta com as seguintes funções.
* **Configuração simplificada WhatsApp:** Configure seu whatsApp usando conexão de dispositivos com camera da aplicação.
* **Configuração simplificada Discord:** Configure canal que deseja enviar a partir do seu Webhook
* **Separação de envio unificados:** Caso deseja selecionar enviar em apenas uma das aplicações, tem possibilidade.
* **Criação de usuários segmentados:** Podendo criar usuários Super Admin, Admin e "Sender"
* **Histórico de envio das mensagens:** Gravado as ações de quem realizou o envio e titulo da mensagem.
* **Smart Splitting:** Mensagens com mais de 2000 caracteres são divididas automaticamente em partes (ex: [1/3], [2/3], [3/3]). Evitando problemas de limitadores da versão Gratuita do Discord.
* **Confirmação de Envio:** Modal de confirmação para mensagens longas.
* **UX:** Contador de caracteres e melhorias visuais.
* **Instalação:** Inicialização automática após setup.
* **Informativo de depedência com vulnerabilidade:** Durante instalação você recebe informação de algum pacote que possua vulnerabilidade.

## 🚀 Instalação
1. `npm install`
2. `npm run prisma:generate`
3. `npm run prisma:migrate`
4. `npm run dev`

## Features futuras
- Envio no Telegram
- Preview de como sua mensagem fica em ambas plataformas
- Melhorias na instalação (Atualmente possuí algumas falhas caso não siga a instalação corretamente.)
- Segmentação dos grupos
- Envio em grupos do Google Chats.
- Exclusão da mensagem partir da plataforma.
- Tela para recuperação de senha.
