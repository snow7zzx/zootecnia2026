# Cabanha Minas Douradas · Montes Claros/MG

Simulador rural 3D em um único arquivo (`index.html`, Three.js r128). Abra no navegador, de preferência no computador, com mouse e teclado. Também funciona no celular, na horizontal.

**Sistema:** semi-intensivo (pasto + cocho)
**Bovinos:** 110 Girolando (leite) · **Ovinos:** 30 Santa Inês (carne)
**Pastagem:** Tifton 85 · 10 piquetes de 0,5 ha para ovinos
**Escala reduzida (esquemático).** Valores do jogo são referências do projeto ou cálculos de simulação, não medições reais. O calendário sanitário deve sempre seguir a orientação do médico-veterinário.

## Controles

### Computador
| Tecla | Ação |
|---|---|
| WASD | andar |
| Mouse | olhar |
| Shift | correr (no voo, acelerar) |
| Espaço | pular |
| **Espaço duas vezes** | **ligar/desligar o voo** |
| Espaço (voando) | subir |
| **Ctrl (voando)** | **descer** (perto do chão, pousa) |
| C | agachar (Ctrl também agacha no chão) |
| Tab | alternar 1ª, 3ª e 2ª pessoa |
| E | interagir; entra e sai do **trator** (galpão de máquinas) e da **picape** (ao lado da casa sede); WASD dirige, Shift acelera |
| F / G | mandar vaca sozinha / soltar vacas |
| Q ou clique | soco |
| N | novo dia |
| P | painel (`[` e `]` ajustam as vacas em lactação) |
| Esc | soltar o mouse / pausar |

### Celular
- Joystick à esquerda para **andar**; arraste a tela para olhar.
- **E** para interagir, **Pular**, **Agachar**, **Câmera**, **Soco**.
- **Voar** liga o voo; **Subir** e **Descer** aparecem enquanto você voa.
- Botões F, G, N, Painel, Info e Menu na faixa superior.

## Layout da fazenda (vista aérea, conforme os slides)
Estrada asfaltada à esquerda, com árvores e o caminhão de coleta de leite. De cima para baixo:
- **Sala de ordenha** ao norte, alinhada com a pista de trato: sala de espera, ordenha em **espinha de peixe** (12 vagas), sala do tanque de resfriamento e farmácia/depósito.
- **Free stall** em duas alas com a **pista de trato** no centro: 2 fileiras de camas por ala (14 camas por fileira, 56 no total), 4 bebedouros e ventiladores. Ao lado, o **galpão de ração** com silo. O galpão de feno e a silagem ficam mais ao leste.
- **Casa sede** com quintal cercado, **picape vermelha** e 2 **quadriciclos** ao lado.
- **Curral** (coberto, com tronco), **bezerreiro** e **aprisco** em fileira. O aprisco tem baias, corredor central, creep feeding, bebedouros e solário.
- **Galpão de máquinas** com trator verde e grade, e **açude com lona**, cercado.
- Milharais ao sul; campo de sorgo e de Tifton 85 (feno), 6 piquetes de bovinos e 10 de ovinos à direita.

## O que o jogo cobre
- **Leite:** 18 L/vaca/dia (referência), ordenha em etapas (pré-dipping, teteiras, ordenha, pós-dipping), tanque, 1 kg de concentrado a cada 3 L acima de 8 L/dia, produção individual (V01 a V08) e diária, vacas em lactação configuráveis.
- **Bezerros:** colostro (10% do peso vivo), 4 L de leite por dia, concentrado inicial e água, cura do umbigo com iodo a 10%, peso e idade, desmame aos 60 dias.
- **Ovinos:** cria (0 a 60 dias, creep feeding), recria e terminação em áreas separadas, abate com 35 kg, flushing, reforço de concentrado na gestação e lactação, 10 piquetes rotacionados.
- **Pastagem:** águas (nov a mar) e seca, entrada com 25–30 cm e saída com 10–15 cm, rotação dos piquetes de ovinos e de bovinos, silagem de milho ou sorgo e feno na seca.
- **Reprodução:** IATF, nascimentos, recria e entrada das novilhas na ordenha.
- **Sanidade:** caneca de fundo preto, CMT, terapia de vaca seca, carrapato e tristeza parasitária, FAMACHA e OPG, vermifugação seletiva, casqueamento e pedilúvio, linfadenite caseosa, vacinas (brucelose B19, clostridioses, raiva, IBR/BVD, leptospirose, ovinos), exames anuais de brucelose e tuberculose, GTA e quarentena na compra.
- **Painel (P):** rebanho, leite, produção individual, alimentação, pastagens, reprodução, saúde, calendário dos próximos 21 dias, calendário sazonal e objetivos.
- **Sistema:** passagem de dias, estações, notificações, tutorial inicial, objetivos e salvamento automático a cada dia (no navegador).

## Animais vivos
Vacas e bezerras andam e pastam dentro dos piquetes, as ovelhas circulam no aprisco, os cordeiros ficam na área da sua fase, as galinhas ciscam perto do galinheiro, o cavalo e os cachorros passeiam pela sede. No céu há urubus, garças perto do açude e passarinhos de vários tamanhos com as asas batendo. Os animais bloqueiam a passagem do jogador; no voo você passa por cima.

## Gráficos
Escolha na tela inicial: Batata, Baixo, Médio ou Ultra. Trocar o gráfico reinicia o jogo.
