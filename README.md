# nginx-proxyReverso-loadBalancer
Projeto simples com o Nginx usando Proxy Reverso e Load Balancer do Fabrício Veronez.

Conteúdo da aula disponibilizada no Youtube do Fabrício Veronez. 

Caso vocês queiram assistir a aula, segue o link: https://lnkd.in/dzzt5FST

Foi feito uso do Nginx como um Proxy Reverso e um balanceador de carga, onde dependendo do subdomínio, ele iria levar para um container docker diferente, exemplo: https://lnkd.in/d6rtPPZx; https://lnkd.in/dUaD9zHZ.

Vale ressaltar também que existia uma aplicação de conversão de temperatura que possuía 3 réplicas onde pelo Nginx também foi feito o balanceamento da carga, onde podíamos adicionar um peso para um container específico ou não.
