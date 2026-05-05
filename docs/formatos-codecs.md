# Formatos e Codecs de Video

## O que e um Codec?

Codec (Compressor/Decompressor) e o algoritmo que comprime e descomprime arquivos de video.
A escolha do codec impacta diretamente na qualidade, tamanho do arquivo e compatibilidade.

## Codecs mais Usados

### Para Edicao (Alta Qualidade)
| Codec         | Container | Caracteristica                          |
|---------------|-----------|-----------------------------------------|
| ProRes 422    | .mov      | Padrao Apple, excelente para edicao     |
| ProRes 4444   | .mov      | Suporta canal alpha (transparencia)     |
| DNxHD/DNxHR   | .mxf/.mov | Padrao Avid, muito usado em broadcast   |
| CinemaDNG     | .dng      | RAW cinematografico                     |

### Para Entrega (Compressao)
| Codec    | Container    | Uso                                   |
|----------|--------------|---------------------------------------|
| H.264    | .mp4/.mov    | Web, redes sociais, streaming         |
| H.265    | .mp4/.mov    | 4K eficiente, menor tamanho           |
| VP9      | .webm        | YouTube, navegadores                  |
| AV1      | .webm/.mp4   | Streaming moderno, alta eficiencia    |

## Containers (Extensoes)

| Container | Compatibilidade                         |
|-----------|-----------------------------------------|
| .mp4      | Universal, web e mobile                 |
| .mov      | Apple ecosystem, edicao profissional    |
| .avi      | Windows legado, baixa compressao        |
| .mkv      | Open source, multiplas faixas de audio  |
| .mxf      | Broadcast e producao profissional       |

## Bitrate Recomendado por Plataforma

| Plataforma  | Resolucao  | Bitrate Recomendado |
|-------------|------------|---------------------|
| Instagram   | 1080x1920  | 3.5 - 5 Mbps        |
| YouTube     | 1920x1080  | 8 - 12 Mbps         |
| YouTube 4K  | 3840x2160  | 35 - 45 Mbps        |
| TikTok      | 1080x1920  | 2 - 6 Mbps          |
| Broadcast   | 1920x1080  | 50+ Mbps            |

## Audio

| Codec  | Uso                             |
|--------|---------------------------------|
| AAC    | Padrao para MP4, web e mobile   |
| MP3    | Legado, ainda muito usado       |
| WAV    | Audio sem compressao, masterizacao |
| FLAC   | Sem perda, arquivamento         |
| PCM    | Audio bruto, producao           |