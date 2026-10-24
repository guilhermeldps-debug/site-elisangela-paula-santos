# Site — Dra. Elisângela Paula Santos

Site institucional da advogada Elisângela Paula Santos (Osasco/SP), com atuação em Direito Condominial, Trabalhista e Previdenciário.

Página única em HTML e CSS, sem dependências de build. Publicado pelo GitHub Pages.

## Estrutura

- `index.html`: o site completo
- `assets/ponte-osasco.webp` e `assets/predio-osasco.webp`: fotos do topo, que se alternam a cada 3 segundos

## Itens a preencher

Os trechos entre colchetes no `index.html` ainda precisam dos dados reais:

- Número da OAB/SP
- Endereço do escritório e horário de atendimento
- Foto profissional

## Formulário de contato

O formulário envia as mensagens por e-mail pelo serviço gratuito FormSubmit (formsubmit.co):
destino principal guilhermeldps@gmail.com, com cópia para epaula78@gmail.com.
No primeiro envio, o FormSubmit manda um e-mail de ativação para guilhermeldps@gmail.com;
é preciso clicar em "Activate Form" uma única vez para os envios começarem a funcionar.
O envio é um POST normal (sem AJAX); depois de enviado, o FormSubmit volta para o site com ?enviado=1 e aparece a confirmação.
