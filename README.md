# CEO: Do Zero ao Império

Jogo mobile de empresário com história, feito pela **Morais Studio**.

Você é filho de um pequeno comerciante que perdeu tudo para o Grupo Vortex. Com R$ 5.000 e o caderno do seu pai, abre o primeiro negócio numa garagem, escolhe o ramo, contrata funcionários de acordo com os cargos daquele ramo e constrói um império até enfrentar quem destruiu sua família.

**Jogar:** https://moraisstudio92-svg.github.io/CEOLIFE/

## Como publicar uma atualização

1. Suba o novo `index.html` com a constante `VERSION` nova.
2. Atualize `version.json` com a mesma versão e uma nota curta (ex.: `{"v":"0.3","nota":"Atualização de novos ramos"}`).

Quem estiver com o jogo aberto vê o aviso **Nova atualização** e o jogo recarrega sozinho em 5 segundos.

## Versão 0.4 — Veículos, beco e estacionamento

- Carros novos (sedã, hatch, SUV, picape, táxi, van) e moto detalhada
- Beco das motos ao lado da loja, com porta lateral para os entregadores
- Estacionamento com clientes que chegam de carro
- Calçada com bancos, árvores e mesinhas
- Área externa com melhorias em níveis (aba no Decorar)

## Versão 0.3 — Tela cheia, horário e decoração

- O jogo é a própria cena, em tela cheia, com botões transparentes por cima
- Lojas com horário de abrir e fechar; à noite a equipe vai embora e o tempo acelera
- Toque em qualquer posto (balcão, fogão, mesa, moto) para subir o nível (+20% por nível)
- Decoração: piso, paredes, plantas, iluminação, quadros e fachada (+4% de receita cada)
- Personagens e ambientes com mais detalhe e sombras; câmera mais afastada

## Versão 0.2 — Cena ao vivo e filiais

- Cena isométrica ao vivo de cada empresa, com cada funcionário na sua função
- Rua com motoboys saindo para entregar, clientes, carros e dia e noite
- Filiais: abra mais unidades da mesma empresa (bônus de rede)
- Tela inicial nova, música calma e atualização automática

## Versão 0.1 — Base do jogo

- Criação do CEO (nome, visual e perfil)
- Prólogo e Ato 1 completo (5 capítulos e escolha final)
- 4 ramos: Alimentação, Moda, Tecnologia e Logística, cada um com 4 cargos
- Candidatos com estrelas, salário, moral e traço de personalidade
- Eventos de decisão (lucro x ética) e o rival Vortex
- Sede que evolui, ganho offline e save automático no aparelho

## Arquivos

- `index.html` — o jogo inteiro (HTML, CSS e JavaScript)
- `version.json` — versão atual, usada pelo aviso de atualização automática
- `manifest.webmanifest` e `icon-*.png` — permitem adicionar o jogo à tela inicial do celular
