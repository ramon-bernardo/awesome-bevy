# Incrível Bevy

Uma lista [incrível](https://github.com/sindresorhus/awesome) de projetos interessantes de Bevy. Se você gostaria de compartilhar o que está fazendo, envie um PR! Sinta-se à vontade para criar novas categorias onde fizer sentido.

## Aprendendo

* [Exemplos Oficiais de Bevy](https://github.com/bevyengine/bevy/tree/master/examples): Aprenda cada recurso do Bevy com o mínimo de exemplos ilustrativos.
* [Folha de Dicas](https://github.com/jamadazi/bevy-cheatsheet): Referência de programação concisa para Bevy!
* [Livro de Métodos](https://github.com/jamadazi/bevy-cookbook): Métodos concisos para tarefas comuns de desenvolvimento de jogos.
* [Criando um clone de Snake](https://mbuffett.com/posts/bevy-snake-tutorial/): Passo a passo de como fazer um clone de Snake.
* [Criando um clone de Xadrez em 3D](https://caballerocoll.com/blog/bevy-chess-tutorial): Passo a passo de como fazer um clone de Xadrez com peças 3D.

## Plugins e Crates
### Entrada (Input)

* [Kurinji](https://crates.io/crates/kurinji): Um plugin para mapear a entrada de hardware. Converte as diferentes entradas do hardware do usuário em ações específicas do jogo, por exemplo. O teclado "Espaço" ou o joystick "A" podem ser mapeados para a ação "Saltar". Isso permite o desacoplamento do código do jogo da API de entrada específica do dispositivo.

### 3D

* [bevy_fly_camera](https://crates.io/crates/bevy_fly_camera): Um plugin para criar uma câmera voadora básica.
* [Bevy-WoW](https://github.com/Tezza48/Bevy-WoW): Um projeto de câmera com o estilo de World of Warcraft.
* [bevy_obj](https://github.com/AmionSky/bevy_obj): Um plugin para carregar ativos com malha do tipo Wavefront (.obj).
* [bevy_mod_picking](https://github.com/aevyrie/bevy_mod_picking): Um plugin para seleção de mouse, facilitando a interação com geometria usando seu mouse ou qualquer outra fonte de fundição de raios.

### 2D

* [bevy_tiled](https://github.com/stararawn/bevy_tiled): Um plugin para renderizar mapas do editor Tiled.
* [bevy_prototype_lyon](https://github.com/Nilirad/bevy_prototype_lyon): Um projeto protótipa para desenhar formas e caminhos 2D, como triângulos, círculos, retângulos, linhas, arcos e beziers.
* [bevy_tilemap](https://github.com/joshuajbouw/bevy_tilemap): Um plugin que permite a renderização de pedaços para mapas baseados em telhas.
* [bevy_prototype_parallax](https://github.com/btrepp/bevy-prototype-parallax): Um plugin protótipo para gerar fundos com rolagem estilo parallax.

### Animação (Animation)

* [bevy_easings](https://crates.io/crates/bevy_easings): Um plugin para atenuar o valor de um componente para outro valor, usado principalmente para animar a transição entre duas transformações, mas pode ser usado para outros componentes.

### UI

* [bevy_ninepatch](https://crates.io/crates/bevy_ninepatch): Um plugin que exibi elementos de interface de 9 patch, podendo especificar como as diferentes partes de um PNG devem crescer.

### Backends

* [prototype_bevy_sdl2](https://github.com/aclysma/prototype_bevy_sdl2): Um protótipo para integração SDL2.
* [bevy_miniquad](https://github.com/smokku/bevy_miniquad): Um plugin que substitui os plugins de janela padrão e renderização por um baseado em [miniquad](https://github.com/not-fl3/miniquad).
* [bevy_doryen](https://github.com/smokku/bevy_doryen): Um plugin que integra Bevy ECS com a biblioteca Ascii roguelike ([doryen-rs](https://github.com/jice-nospam/doryen-rs)) com apoio nativo e WASM.
* [bevy_webgl2](https://github.com/mrk-its/bevy_webgl2): Um plugin backend de renderização WebGL2 com alvo o WASM.

### Física (Physics)

* [bevy_rapier](https://github.com/dimforge/bevy_rapier): Um plugin de física 2D e 3D. Mantido pelos desenvolvedores do Rapier.
* [physme](https://github.com/walterpie/physme): Um projeto de física simplista para simulação 2D e 3D. Fisicamente impreciso de acordo com a mecânica newtoniana, mas satisfatório e fácil de usar.

### Networking

* [bevy_prototype_laminar_networking](https://github.com/ncallaway/bevy-prototype-laminar-networking): Um plugin protótipo de rede usando `laminar` como meio de transporte, adiciona opções simples de confiabilidade, pedidos e conexão virtual em cima do soquete UDP.
* [bevy_prototype_simple_net](https://github.com/0x22fe/bevy_prototype_simple_net): Um plugin protótipo de rede que pode criar sistemas cliente/servidor sobre TCP ou UDP.
* [bevy_networking_turbulence](https://github.com/smokku/bevy_networking_turbulence): Um plugin de rede usando [naia-socket](https://github.com/naia-rs/naia-socket) e [turbulence](https://github.com/kyren/turbulence). Permite a troca de mensagens brutas e pacotes nativos Linux/Windows (UDP/UDP) e também no navegador/WASM (UDP/WebRTC).

### Ferramentas de Desenvolvimento (Development Tools)

* [bevy-contrib-inspector](https://github.com/jakobhellermann/bevy-contrib-inspector): Um projeto que possibilita a edição de forma visual de sua estrutura de recursos, mostrando-a em seu navegador.

### Ajudantes (Helpers)

* [bevy_contrib_colors](https://crates.io/crates/bevy_contrib_colors): Um projeto simples com a paleta de cores Tailwind.
* [bevy_prototype_inline_assets](https://crates.io/crates/bevy_prototype_inline_assets): Um plugin para agrupar ativos (assets) em seu binário.

### Jogos (Games)

* [bevy_nbody](https://github.com/thallada/bevy-nbody): Um projeto que simula n-corpos usando Bevy para renderização e [bigbang](https://docs.rs/bigbang) para os cálculos.
* [flock-rs](https://github.com/JohnPeel/flock-rs): Um projeto que gera comportamentos de direção e bando.
* [bevy_pong](https://github.com/SuperiorJT/bevy_pong): É o Pong! Criado com base no exemplo de "breakout" e colisão modificada.
* [bevy-tetris](https://github.com/8bit-pudding/bevy-tetris): É o Tetris!
* [snake_bevy](https://github.com/mtKeller/snake_bevy): É o Snake!
* [i_sjon_kan_ingen_hora_dig_skrika](https://gitlab.com/TheZoq2/i_sjon_kan_ingen_hora_dig_skrika): Um projeto de simulador de barco pirata a remo sueco 2020.
* [labyrinth-game](https://github.com/insrcd/labrynth-game): Um projeto de mercado simulado com roguelike.
* [bevy_sokoban](https://github.com/ropewalker/bevy_sokoban): É o Sokoban!
* [per_spatium](https://gitlab.com/BottledByte/per-spatium): Um projeto de jogo de tiro em uma nave espacial.
* [bevy_rider](https://github.com/bonsairobo/bevy_rider): É o Line Rider!
* [bevy_squares](https://github.com/TheNeikos/bevy_squares): Um projeto remake dos jogos Threes.
* [Kataster](https://github.com/Bobox214/Kataster): Um projeto de jogo espacial de tela única.
* [Keep Inside](https://github.com/davidB/ld47_keep_inside): Um projeto estilo Pong porém solo em um círculo (feito para Ludum Dare 47).
* [Keep Moving and Nobody Burns](https://github.com/mockersf/kmanb): Um projeto de jogo estilo bomberman porém contra o tempo (feito para Ludum Dare 47).
* [SiO2](https://github.com/dmitriy-shmilo/sio2): Um projeto remake do jogo Powder Toy.
* [Robbo](https://github.com/mrk-its/bevy-robbo): Um projeto do jogo Atari Robbo de 8 bits, sendo executado nativamente e no navegador.

### Aplicativos (Apps)

* [bevy-calc](https://github.com/PravinKumar95/simple-calc): Um projeto que cria uma calculadora simples.