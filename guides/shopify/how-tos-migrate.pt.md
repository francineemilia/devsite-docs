# Como migrar para a nova versão do plugin Mercado Pago

Saiba como migrar para a versão atual do plugin do Mercado Pago para Shopify.

1. Vá para a sua loja [Shopify](https://accounts.shopify.com/store-login).
2. No painel administrativo da loja, clique em **Configurações**.
3. Uma vez lá, selecione a opção **Pagamentos**. 
4. Em **Formas de pagamento adicionais**, clique em **Adicionar formas de pagamento**.
5. Digite "Checkout Mercado Pago" na barra de busca. Após encontrá-lo, clique na opção **disponível**.
6. Digite as suas **credenciais de produção** (`public key` e `access token`) nos campos que as solicitam. Lembre-se de ter suas [credenciais](/developers/pt/docs/shopify/additional-content/credentials) à mão. 
7. No próximo passo, você poderá selecionar as imagens dos meios de pagamento que deseja exibir na loja. **Importante: estas imagens são apenas para fins ilustrativos e não implicam a ativação do método de pagamento selecionado**.
8. Por último, a loja oferecerá a opção **habilite o modo de teste**. Ao ativar essa opção os pedidos finalizados com o Checkout Pro **não serão pedidos reais**. Ou seja, serão pedidos de teste que, mesmo finalizados, não terão seus status atualizados na plataforma e não aparecerão no painel do Mercado Pago na conta do vendedor.
9. Ao finalizar, clique em **Ativar Mercado Pago**.

> Neste exato momento você terá ambas as versões do plugin instaladas em seu site. Isso servirá para a sua loja ficar sem nenhum meio de pagamento enquanto estiverem sendo realizadas as etapas de migração.

10. Vá para sua loja [Shopify](https://accounts.shopify.com/store-login).
11. No painel administrativo da loja, clique em **Configurações**.
12. Uma vez lá, selecione a opção **Pagamentos**. 
13. Em **Formas de pagamento adicionais**, localize o antigo plugin do Mercado Pago e desative-o.

> WARNING
>
> Atenção
>
> Tenha cuidado para não desinstalar a nova versão.