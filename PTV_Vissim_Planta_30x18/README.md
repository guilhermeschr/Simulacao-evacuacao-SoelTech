# Modelo preliminar — planta 30 × 18 m

Arquivo `SoelTech_Planta_30x18.inpx` e seu layout `.layx`: um pavimento com área de circulação e paredes 3D, baseado na imagem `planta_referencia.png`.

O contorno de 30 × 18 m e as dimensões de sala indicadas no quadro orientaram o traçado. A planta é esquemática e não define todas as posições de portas: a cota de 10 m e os vãos devem ser conferidos. As posições das salas 01 a 03 e alguns vãos foram interpretados. Altura de parede 2,70 m e espessura 0,12 m são hipóteses para visualização. Há apenas um pavimento na imagem; não foi inventado outro nem uma escada.

As portas foram revistas contra os vãos visíveis no desenho. O arquivo agora representa quatro aberturas de 2,00 m (duas no perímetro, uma para a sala 05 e uma entre as salas 09 e 10) e oito aberturas de 1,00 m (salas 01, 02, 03, 04, 06 e 07, entrada da sala 09 e passagem entre 08 e 09). As posições e larguras continuam interpretações do croqui: o próprio desenho pede confirmação em obra. As portas estão representadas por vãos livres, sem folhas ou movimento de abertura.

`portas_ajustadas.png` mostra esses vãos com as letras D para duplas e S para simples. Uma verificação geométrica aproximada em grade encontrou conexão entre a área aberta e o interior das dez salas, mas não substitui uma simulação no Vissim.

Esta é uma geometria preliminar, não um modelo de evacuação validado: o arquivo não contém entradas de pedestres, rotas nem resultados.

O arquivo INPX é a versão mais recente salva no Vissim. O desenho de revisão foi gerado em 27/10 e deve ser comparado com eventuais alterações posteriores no INPX.
