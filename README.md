# GiroCampo

**Gestão inteligente de equipes de vendas em campo**  
Protótipo inicial desenvolvido pela Orange Code.

## O que existe nesta primeira versão

- Login demonstrativo
- Painel com indicadores e destaques de vendedores
- Cadastro e edição de vendedores
- Cadastro e edição de equipes
- Registro e edição de vendas
- Metas gerais e metas por equipe
- Resumo financeiro demonstrativo e comissões estimadas
- Relatórios resumidos e exportação CSV
- Layout responsivo para desktop e celular

## Acesso de demonstração

- **E-mail:** `admin@girocampo.app`
- **Senha:** `girocampo123`

## Dados e limitações atuais

Esta versão não usa banco de dados nem API. O conjunto inicial de vendedores, equipes e vendas está definido no próprio `index.html`. As alterações feitas na interface ficam em `localStorage` do navegador; a sessão fictícia usa `sessionStorage`.

Isso significa que:
- Os dados não são compartilhados entre dispositivos ou navegadores.
- Limpar o armazenamento do navegador pode apagar as alterações.
- O login é apenas demonstrativo e **não deve ser usado para proteger dados reais**.
- Os números, produtos, equipes, metas e comissões são fictícios.
- O gráfico semanal atual é ilustrativo, não é calculado com os registros de vendas.

## Publicação estática

O projeto é um HTML estático, sem etapa de build ou dependências externas. Para publicar no Netlify, use a raiz do repositório como diretório de publicação e deixe o comando de build vazio.

## Próximas etapas

1. Validar o fluxo visual e os campos de cadastro.
2. Definir regras reais para vendas, metas e comissões.
3. Modelar a estrutura de usuários, permissões, vendedores, equipes, vendas e fechamento financeiro.
4. Substituir o armazenamento local por um banco de dados e autenticação seguros antes de qualquer operação real.
