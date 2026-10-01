# iRap — Chamado do Rap

Aplicativo de batalhas de rap para Android, iOS e web.

## O que já está pronto

- Arena 1x1.
- 3, 4 ou 5 rounds.
- Critérios Flow, Rima e Impacto.
- Placar acumulado entre todos os rounds.
- Histórico de batalhas.
- Persistência local no navegador e no aplicativo mobile.
- Interface dark com identidade iRap.
- Projeto Expo/React Native em `mobile/`.
- Configuração EAS para builds Android e iOS.

## Aplicativo mobile

Entre na pasta `mobile/`:

```bash
npm install
npx expo start
```

Builds de produção:

```bash
npm run build:android
npm run build:ios
```

Para gerar os arquivos finais e publicar nas lojas, o EAS precisa estar conectado às contas do Google Play Console e Apple Developer do proprietário do aplicativo.

### Identificadores

- Android: `com.leandrozzm3.irap`
- iOS: `com.leandrozzm3.irap`

## Estrutura

- `index.html` — versão web.
- `styles.css` — visual web.
- `app.js` — lógica da versão web.
- `mobile/App.js` — aplicativo Android/iOS.
- `mobile/app.json` — configuração Expo.
- `mobile/eas.json` — perfis de build e publicação.
- `mobile/package.json` — dependências e comandos.

## Publicação

A publicação real na Google Play e na App Store exige contas de desenvolvedor, dados legais da empresa/pessoa responsável, certificados/credenciais das lojas e revisão das plataformas. O código e a configuração do aplicativo estão preparados para essa etapa, mas essas credenciais não podem ser inventadas ou substituídas por credenciais de terceiros.

## Próximas evoluções

Backend, login, perfis de MCs, ranking online, salas em tempo real, votação pública, notificações e armazenamento em nuvem.
