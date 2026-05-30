# Dashboard - Terceiras

Dashboard HTML publicado via GitHub Pages.

## Arquivos

- `index.html`: página principal do dashboard.
- `dados_terceiras.json`: base de dados consumida pelo dashboard.

## Publicação manual - Opção A

1. Criar um repositório no GitHub chamado `dashboard-terceiras`.
2. Enviar os arquivos `index.html` e `dados_terceiras.json` para a raiz do repositório.
3. No GitHub, acessar Settings > Pages.
4. Em Build and deployment, selecionar:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root
5. Salvar e aguardar o link do GitHub Pages.

## Atualização manual dos dados

Sempre que a base mudar:

1. Gerar um novo arquivo `dados_terceiras.json`.
2. Substituir o arquivo antigo no repositório GitHub.
3. Manter exatamente o mesmo nome: `dados_terceiras.json`.
4. Recarregar o dashboard no navegador.

## Observação

O GitHub Pages público permite acesso a qualquer pessoa que tenha o link.
