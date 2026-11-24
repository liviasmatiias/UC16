# Atividade Prática — Avaliação de UX/UI

## 1ª Heurística de Nielsen: Visibilidade do Status do Sistema

**Objetivo:** Navegar por um e-commerce fictício, simulando uma experiência completa de compra. Durante a navegação, vocês deverão identificar problemas relacionados à visibilidade do status do sistema.

---

## 1. Cadastro e Login

- [X] Criar uma nova conta.
- [X] Tentar cadastrar uma conta com dados inválidos.
- [X] Fazer login com os dados corretos.
- [X] Tentar fazer login com senha incorreta.
- [X] Sair da conta e entrar novamente.

## 2. Navegação e Pesquisa

- [X] Pesquisar um produto pelo nome.
- [X] Pesquisar um produto que não existe.
- [X] Aplicar filtros no catálogo.
- [X] Alterar a ordenação dos produtos.
- [X] Navegar entre diferentes produtos.

## 3. Produtos e Favoritos

- [X] Abrir os detalhes de um produto.
- [X] Adicionar um produto aos favoritos.
- [X] Remover um produto dos favoritos.
- [X] Adicionar diferentes produtos ao carrinho.
- [X] Adicionar o mesmo produto mais de uma vez.

## 4. Carrinho de Compras

- [X] Abrir o carrinho.
- [X] Aumentar a quantidade de um produto.
- [X] Diminuir a quantidade de um produto.
- [X] Remover um produto do carrinho.
- [X] Conferir o valor total da compra.

## 5. Finalização da Compra

- [X] Iniciar o processo de checkout.
- [X] Preencher os dados de entrega.
- [X] Tentar continuar com campos incompletos.
- [X] Selecionar uma forma de pagamento.
- [X] Finalizar a compra simulada.
- [X] Verificar se existe confirmação do pedido.

## 6. Conta e Pedidos

- [X] Consultar os dados da conta.
- [X] Procurar o histórico de pedidos.
- [X] Verificar as informações de uma compra.
- [X] Tentar identificar o status do pedido.

---

## 7. O que observar durante os testes?

Durante cada ação, respondam às seguintes perguntas:

1. O sistema informou que recebeu minha ação?
2. Consigo identificar o que está acontecendo?
3. Sei se a operação foi concluída, está em andamento ou apresentou algum erro?
4. O sistema fornece informações suficientes para que eu saiba o que fazer em seguida?

---

## 8. Entrega da Atividade

Cada aluno ou grupo deverá identificar **pelo menos 8 problemas de usabilidade** relacionados à primeira heurística de Nielsen.

Para cada problema encontrado, registre:

| Item | Descrição |
|---|---|
| **Tela ou funcionalidade** | Onde o problema aconteceu? |
| **Ação realizada** | O que vocês estavam tentando fazer? |
| **Problema identificado** | Qual informação o sistema deixou de apresentar? |
| **Solução proposta** | Como a interface poderia ser melhorada? |

### Modelo de Registro dos Problemas

| Nº | Tela/Funcionalidade | Ação realizada | Problema identificado | Solução proposta |
|---|---|---|---|---|
| 1 | tela de Cadastro| Cadastrar clientes | Nao avisa confirmação de cadastro| Adicionar um servico de cadastro confirmado|
| 2 | Inserir o item no carrinho | adicionado no carrinho | adiciona e nao confirma se foi ou nao adicionado | inserir alguma mensagem como "inserido no carrinho com sucesso|
| 3 | Entrar na conta | Entrou na conta | nao indentifica de entrou na conta | ter uma confirmacao de login|
| 4 | favoritar algum item | favoritei o produto | nao alterou nem pintou o coracao, e nao tem nenhuma aba de favoritos | criar uma mensagem de favoritado e um campo para ver todas as pecas  |
| 5 | entrar na conta | inserir a senha ou email errado | nao comunica o erro da senha ou do email | comunicar o erro para o usuario saber o que fazer |
| 6 | cadastrar na conta | inserir senha e colocar no confirmar senha outra diferente | nao comunica a incompatibilidade para o usuario | comunicar o erro da senha na hora da confirmção|
| 7 | carrinho | aumentar ou diminuir quantidade | a tela tela nao atualiza automaticamente e voce deve sair dela e voltar para ai sim atualizar | atualizar a cada clique da tela|
| 8 | Finalizacao Compra | Clique em confirmar pedido | A compra foi registrada, mas nao apareceu nenhuma confirmacao de conclusao | mostrar uma tela informando que o pedido foi realizado com sucesso |

---

## 9. Orientações Importantes

**Atenção:** Não basta escrever que determinada funcionalidade não funcionou. É necessário explicar qual informação está faltando e como o sistema deveria comunicar seu estado ao usuário.

### Desafio Final

O site possui problemas intencionais de usabilidade. Vocês deverão descobri-los sem receber dicas sobre onde estão.

O objetivo não é apenas identificar falhas, mas também **propor soluções que tornem a experiência do usuário mais clara, intuitiva e confiável.**