<!-- # H1
1. Lista
# H2
**Negrito**
- Tópicos -->

# Projeto Integrador - Larissa e Vinicius

Desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Alunos: [Larissa Cristina Bileski](github.com/larissabileski) e [Vinicius Henrique da Silva](github.com/viniihds). 

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)]()
-   [Backend]()
-   [Frontend]()

<!-- # Modelos de Sistemas

## 1- Ponto de Vendas (PDV)

**Gerenciamento de vendas para uma padaria**

O nosso cliente, Sr. Genival, tem uma padaria de bairro chamada padaria Pão Genial e, devido a qualidade de seus produtos, ela está crescendo rapidamente. Recentemente, ele contratou mais funcionários para atendimento, caixa, panificação, etc.
Assim, atualmente, ele consegue concentrar seus esforços para melhorar a gestão da padaria. Para isso, ele quer instalar um sistema de controle de vendas que permita ao caixa lançar as vendas realizadas. Como sua intenção
é melhorar a gestão do negócio, é muito importante que ele consiga ter
relatórios, como por exemplo, de vendas.-->

# Situação Problema

-   **Introdução**: O sistema será desenvolvido para a empresa Fiberblu. Presente há 28 anos no mercado, é o maior comercio de tanques de fibra na região Sul do país. O dono Odair, o gerente comercial Ednilson, a diretora financeira, e os representantes da empresa, são os principais funcionários e os que terão acesso ao sistema.
-   **Situação-problema**: Atualmente a empresa funciona da seguinte forma: o representante anota o pedido em uma planilha, em seguida, o pedido é enviado por email e depois cadastrado no sistema. O sistema realiza o relatório do pedido e avisa a equipe de estoque. No dia do carregamento, o sistema fatura o pedido, desconta do estoque e é emitido o boleto. Atualmente, no sistema utilizado não há como fazer o pedido direto no sistema, além disso, o sistema também não emite o boleto diretamente para o cliente, nem avisa se o boleto está vencendo ou se foi pago.
-   **Conclusão**: Notamos a falta de alguns recursos no atual software utilizado pela empresa, como por exemplo: O sistema não envia nem notifica o cliente em relação ao boleto, seja para avisar sobre o prazo do pagamento ou eventual vencimento. Outra dificuldade que percebemos foi que, o sistema não tem uma opção para fazer pedidos. O cliente faz o pedido por uma planilha, envia por e-mail, e os administradores do sistema precisam registrar o pedido.

# Descrição da proposta

**Alguns pontos importantes a se destacar são:**

-   **Qual o foco de ação do software** : Acessar o relatório de vendas, controle de estoque, gerir ganhos e despesas, gerenciar cota de representantes, emissão de boletos após o faturamento dos pedidos e mensagens automáticas.
-   **Os níveis de usuário do sistema**: O acesso ao sistema será restrito ao dono, ao gerente comercial, ao diretor financeiro e aos representantes da empresa. O dono terá acesso a todas as ações do software como administrador, o gerente comercial terá acesso ao relatório de vendas, ao controle de estoque e ao controle de ganhos e despesa, o diretor fincanceiro terá acesso ao relatório e histórico de vendas, ao gerenciamento de ganhos e despesas e as emissões de boletos, e os representantes terão acesso ao estoque e aos pedidos efetuados no sistema.
-   **O que poderá ser feito no software**: O software será utilizado para: acessar relatório e histórico de vendas, controle de estoque, gerir ganhos e despesas, gerenciar cota de representantes, emissão de boletos após o faturamento dos pedidos, mensagens automáticas após algumas ações( faturamento, emissões de boletos, vencimento de boletos ).

# Regras de negócio
- **RN01 - Requisito do Cliente:** Apenas pessoas jurídicas podem efetuar pedidos.
- **RN02 – Inserir Produtos no Pedido:** Para inserir um produto na pedido, é necessário que o produto esteja cadastrado no sistema e que a quantia comprada seja acima de zero.
- **RN03 - Valor Minimo do Pedido:** Só serão efetuados pedidos acima de R$1000,00.
- **RN04 - Cadastro do Pedido:** Para o pedido ser cadastrado no sistema, ele deve ser realizado por um representante da empresa.
- **RN05 - Controle do Estoque:** O produto é descontado do estoque apenas no dia do carregamento.
- **RN06 - Envio do Pedido:** O pedido só é enviado após o faturamento do pedido.
- **RN07 - Relatório de Vendas:** Só terão acesso ao relatório de vendas os administradores (dono, gerente comercial e diretor financeiro).
- **RN08 - Cota para Representantes:** A cota para novos representantes é de 50 peças por mês.
- **RN09 - Cota para Representantes:** Para representantes antigos a cota é de 15% a mais do que o vendido no mesmo mês do ano anterior.

<!-- 
- **RN07 – Impressão de Orçamento:** Com as informações do
orçamento registradas, a atendente deve imprimir o orçamento e
repassar ao cliente para aprovação, e caso o cliente aprovar, a atendente deve solicitar a sua assinatura para aprovar a execução do serviço.
- -->

# Requisitos funcionais

**Entradas:**
- **Registro de usuário**: O usuário deve ser cadastrado pela sua função, para ter acesso a determinadas telas.

- **Registro de Produto**: No cadastro do produto deverá ser informado o código do produto, sua cor, material, tamanho e valor.

**Processos:**
- **Autenticação de usuário**: Dados necessários para autenticação: login, senha e função
- **Registro de pedido**: O pedido deve ser cadastrados identificando o nome da empresa, produtos pedidos, valor do pedido e vendedor que efetuou o pedido.
**Saidas:**
- Relatório de vendas
- “Log de usuários autenticados
<!-- 
- **R.F. 01 - Autenticação de usuário:** tem como propósito autenticar o acesso ao sistema, verificando se o usuário pode acessá-lo e, caso possa, o direcionando
para a página principal de seu perfil de acesso. 
  - **Dados necessários:** login, senha, nível de permissão. 
  - **Usuários:** todos os níveis de usuário.-->
  