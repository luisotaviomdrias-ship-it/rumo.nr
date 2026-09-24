# Ebook Rumo

A landing page e o painel apresentam a nova edição visual do ebook ilustrado em PDF (27 páginas, sumário clicável, imagens, diagramas e exercícios resolvidos).
Somente a amostra pública de quatro páginas fica em `assets/rumo-ebook-amostra.pdf`, com autorização explícita do proprietário.
O PDF completo deve ser entregue pela área de membros da Cakto/Kiwify e não deve entrar neste repositório público.

## Ativar venda
1. Cadastre o ebook como produto separado, defina preço e carregue o PDF completo na plataforma.
2. Em `ebook-config.js`, configure `checkoutUrl` com o link HTTPS do produto em `pay.cakto.com.br` ou `pay.kiwify.com.br`.
3. Confirme em uma compra de teste da plataforma a entrega do ebook e eventual order bump.
4. Publique e confira os botões na landing page e no painel.

Sem URL válida, a interface informa “Compra disponível em breve”. Não simula uma compra. A compra do ebook não concede assinatura. Os quatro checkouts e a validação de acesso do SaaS permanecem independentes.

## Edição visual de setembro de 2026
A capa pública é renderizada da página 1 da nova edição. A amostra contém apenas as páginas 1, 5, 16 e 18 do ebook, identificadas como amostra. O caderno financeiro preenchível é um complemento separado; não está incluído no ebook principal nem publicado neste repositório.
