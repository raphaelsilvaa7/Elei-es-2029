🗳️ Simulador de Urna Eletrônica + Painel SISTOT
Um simulador web interativo e responsivo da Urna Eletrônica Brasileira, integrado a um painel de apuração e totalização de votos em tempo real (SISTOT). Desenvolvido com foco em fidelidade visual, rapidez de resposta e funcionamento 100% independente de arquivos externos.

✨ Funcionalidades
Interface Fiel ao Padrão TSE: Tela de votação com exibição dinâmica de números, nome do candidato, partido, cargo, instruções de rodapé e mensagens de Voto em Branco e Voto Nulo.
Áudio Oficial Sintetizado (Web Audio API): Bipes ao pressionar as teclas numéricas e o clássico som de encerramento ("FIM") gerados nativamente pelo navegador, sem necessidade de arquivos .mp3 externos.
Painel SISTOT em Tempo Real: Dashboard integrado logo abaixo da urna que contabiliza e exibe instantaneamente os votos válidos, brancos, nulos, total de eleitores e barras de progresso com as porcentagens de cada candidato.
Sistema Inteligente de Fotos (3 Camadas):
Fallback Vetorial (Offline): Retratos em SVG embutidos no código que carregam instantaneamente (0ms) e evitam ícones de imagem quebrada.
Integração com a Wikipédia: Busca automática das fotos oficiais atualizadas através da API REST da Wikipédia em Português.
Upload Customizado: Botões dedicados no painel para carregar fotos locais diretamente do computador ou celular.
Design Responsivo: Layout adaptável que posiciona a tela e o teclado lado
