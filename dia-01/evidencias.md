# Evidências

## Documento de Evidências de testes

**Título do Teste:** Página inicial de um site de notícias

**Data do Teste:** 09/10/2023

**Responsável pelo Teste:** Tayná Vieira

**Objetivo do Teste:** Avaliar a qualidade e a usabilidade da página inicial do site R7 Notícias por meio de testes manuais.

### Ambiente de teste

**Ambiente:** Produção

**Ferramentas utilizadas:**

- Navegadores da web (por exemplo, Google Chrome, Mozilla Firefox, Microsoft Edge)
- Dispositivos (computador desktop, tablet, smartphone)
- Jira para registro de documentações

### **Passos do Teste**

1. **Carregamento da página**

- **Resultado Esperado:** A página inicial deve carregar sem erros e de fora rápida (web e mobile (android))
- **Resultado Real:** Ao digitar o link na caixa de pesquisa do navegador Google Chrome, não houve intercorrências no redirecionamento. A página do site de notícias R7 carregou conforme esperado, em tempo menor que 5 segundos.
- **Observações:** Passou

1. **Layout e Design**

- **Resultado esperado:** O layout deve ser atraente, bem organizado e consistente em diferentes dispositivos (web e mobile (android))
- **Resultado Real:** Possui várias  caixas de notícias vazias dispersas entre um conteúdo e outro. O usuário pode tentar clicar e entender que é um erro.

[caixa vazia.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/4f43c08b-ef31-417b-90d7-95cb31a1ce18/7206433c-78b4-437a-8217-054f1c861065/caixa_vazia.png)

- **Observações:** Pendente para ajustes

1. **Manchetes e Noticias em destaque**

- **Resultado esperado:** Todas as manchetes e notícias em destaque devem ser acessíveis e levar ao conteúdo completo dentro da mesma página.
- **Resultado real:**

1. No inicio do site existe uma tarja apresentando a previsão do tempo, e ao direcionar o mouse em cima, especificamente da palavra São Paulo, dá-se a impressão de que clicando, terei mais detalhes do tempo, porém ao efetivamente clicar, apenas se apresenta uma tela sombreada e nada mais, sendo possível ter mais informações sobre a previsão do tempo apenas clicando na opção ‘previsão completa’.

[previsão do tempo.zip](https://prod-files-secure.s3.us-west-2.amazonaws.com/4f43c08b-ef31-417b-90d7-95cb31a1ce18/8a1ed679-6026-4fe0-824e-1224938cc056/previso_do_tempo.zip)

1. Ao explorar as notícias dispostas na seção ‘Últimas’, existe um redirecionamento para sites diversos, sem qualquer aviso prévio. Na versão mobile, já existe uma mensagem que trás outro contexto para este cenário, é sinalizado como ‘você pode gostar’ e ‘link promovido por taboola’

[redirecionamento para sites desconhecidos.zip](https://prod-files-secure.s3.us-west-2.amazonaws.com/4f43c08b-ef31-417b-90d7-95cb31a1ce18/cb2aa570-bbf0-48f0-85a6-ca7b46db00b3/redirecionamento_para_sites_desconhecidos.zip)

[Versão Mobile - Seção Últimas.jpeg](https://prod-files-secure.s3.us-west-2.amazonaws.com/4f43c08b-ef31-417b-90d7-95cb31a1ce18/b6d3156c-186f-4c39-b624-aff4e7e36590/Verso_Mobile_-_Seo_ltimas.jpeg)

- **Observações:** Pendente para ajustes.

1. **Funcionalidades Iterativas:**

- **Resultado esperado:** As funcionalidades iterativas como caixas de pesquisa, redirecionamento para redes sociais e plugin de tradução de conteúdo em libras, devem funcionar corretamente.
- **Resultado real:** Durante a navegação obtiveram os resultados esperados. Redirecionamentos em 4 segundos.

- **Observações:** Passou

1. **Responsividade e Dispositivos Móveis:**

- **Resultado esperado:** A página deve ser responsiva e exibir bem em dispositivos móveis.
- **Resultado real:** Site desempenhou bem em um celular samsung-S20, desktop, e notebook.
- **Observações:** Passou
