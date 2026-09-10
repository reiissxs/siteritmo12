# Ritmo 12 — Landing Page

Landing page independente do aplicativo.

## Arquivos
- `index.html` — página de vendas completa e responsiva
- `assets/ritmo12-logo.png` — logo do Ritmo 12
- `vercel.json` — configuração mínima para deploy na Vercel

## Fluxo do simulador
1. Usuário informa sexo, idade, peso, altura e atividade.
2. A página calcula TMB pela equação de Mifflin–St Jeor.
3. Mostra uma animação de processamento.
4. Exibe TMB e gasto energético diário estimado.
5. Exibe prévia da dieta borrada e CTA para os planos.

## Planos implementados
- Mensal: R$ 14,90/mês
- Vitalício em destaque: R$ 27,90 pagamento único
- Ao selecionar mensal: aparece oferta de upgrade para vitalício por R$ 19,90 total (+R$ 5 sobre o primeiro pagamento mensal).

## Checkout
Os botões estão funcionais na interface, mas não apontam para um gateway porque nenhum link de checkout foi fornecido. Substitua o evento de `#checkoutBtn` pelo redirecionamento do gateway escolhido.
