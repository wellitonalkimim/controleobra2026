# Controle de Obra Profissional - PWA

Este pacote contém a versão de aplicativo web instalável do sistema.

## Arquivos principais
- index.html: sistema principal
- manifest.json: configuração do aplicativo
- service-worker.js: cache/offline básico
- icons/: ícones do aplicativo

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para o repositório.
3. Vá em Settings > Pages.
4. Em Source, escolha "Deploy from a branch".
5. Escolha a branch main e a pasta /root.
6. Salve e aguarde o link ser gerado.

## Como instalar no celular

### Android
1. Abra o link no Google Chrome.
2. Toque nos três pontos.
3. Toque em "Adicionar à tela inicial" ou "Instalar app".

### iPhone / iOS
1. Abra o link no Safari.
2. Toque em compartilhar.
3. Toque em "Adicionar à Tela de Início".

## Observação importante
Este app usa localStorage do navegador. Para uso simples e gratuito, funciona bem.
Para múltiplos clientes acessando dados sincronizados em aparelhos diferentes, o próximo nível é integrar banco de dados online, como Firebase/Supabase.
