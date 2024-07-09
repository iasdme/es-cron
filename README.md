# Temporizador Escola Sabatina
<a target="_blank" href="https://creativecommons.org/licenses/by-sa/4.0/deed.pt-br"><img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-sa.png" alt="drawing" height="28"/></a> <a target="_blank" href="https://github.com/jeanCarloEM"><img src="https://img.shields.io/badge/-JeanCarloEM-2b92db?style=for-the-badge&logo=github" alt="drawing"/></a> <a target="_blank" href="#"><img src="https://img.shields.io/badge/-Demo-red?style=for-the-badge&logo=youtube" alt="drawing"/></a>

Este é um vídeo em 4k feito para marcar tempo e "ritmo" da lição da escola sabatina, servindo como um auxílio aos professores. Ele dedica 7 (sete) minutos para cada dia da lição (7x7), totalizando 49 minutos.

Para evitar interrupções no raciocínio ele é silêncioso, exceto a cada 7 (sete) minutos onde há emissão sonora de clocks de relógio (sutis); e quando resta apenas 7 (sete) e 1 (um) minuto(s) - há aviso em locução e melodia, sendo melodia constante apenas a partir de 1 (um) minuto restante. Assim, ao executá-lo, deixe o canal de som aberto sem preocupações.

## Recurso externo

Recursos grandes - geralmente vídeos - não estão inclusos e devem ser baixados à parte:

- <a href="https://www.youtube.com/watch?v=-YQfZntuPeQ" target="_blank">Partículas<a>

### Vídeos do youtube

Vídeos do youtube em 4k sem perda utilizam o codec VP9 (webm) e quando baixados geralmente estão com extensão ```.mkv``` ou ```.webm```. Estes arquivos não podem(iam), até a data desta publicação, ser importados na suite Adobe.

Por isso, há na pasta raíz o executável ```converter.bat``` (para windows) contendo o comando para converter, sem perdas, arquivos 4k baixados do youtube para o codec h264 (importável no After Efftects). O comando utiliza o programa gratuito <a href="https://ffmpeg.org" target="_blank">ffmpeg<a>, que deve ser instalado previamente. 

Execute-o assim:

```
converter.bat <path-to-file>
```

Este ```.bat``` simplesmente executa o seguinte comando, que você também pode executar diretamente:

````
ffmpeg -i %1 -y -vcodec libx264 -qp 0 -pix_fmt yuv420p -acodec copy "%1.mp4"
````

## Criador/contribuidor original

<a href="https://github.com/jeanCarloEM" target="_blank">JeanCarloEM<a> | www.jeancarloem.com