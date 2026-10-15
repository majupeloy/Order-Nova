# Order-Nova
O sistema Order Nova foi desenvolvido para otimizar o fluxo de pedidos na cafeteria (cliente fictício para desenvolver o projeto de um problema real). Ele permite que o cliente realize todo o processo diretamente no tablet, selecionando itens, definindo quantidades, escolhendo entre pedidos personalizados ou combos pré-definidos. O pagamento pode ser efetuado via PIX, cartão de crédito ou dinheiro. 
Após a confirmação do pagamento, a nota fiscal é gerada automaticamente e o pedido é direcionado ao balcão e à cozinha. O sistema atualiza o status do pedido em tempo real, indicando quando está em preparo e, posteriormente, liberado para retirada, garantindo organização, eficiência e melhor experiência para o cliente.

* Para este projeto será incrementado seguintes métodos de padrão-objeto:

# Padrão Builder
Utilizado para pedidos personalizados, onde o cliente escolhe os itens, quantidades e combinações. O Builder permite montar o pedido passo a passo, de forma flexível, com diferentes componentes.
# Factory Method
* Utilizado para combos predefinidos, onde o sistema cria o objeto de pagamento/combinação com base em uma classe concreta, sem permitir remoções.
* O Factory Method é usado para criar o objeto de pagamento de acordo com a forma escolhida pelo cliente, encapsulando a lógica de criação e facilitando a manutenção do código.
