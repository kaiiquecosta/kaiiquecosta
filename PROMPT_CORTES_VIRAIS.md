# Prompt padrão: cortes virais (YouTube + TikTok/Shorts)

Copie tudo dentro da caixa abaixo, preencha os campos entre `[colchetes]` e cole no chat novo.

```
Quero que você edite um vídeo para YouTube e TikTok/Shorts no estilo viral
(MrBeast / IShowSpeed): cortes rápidos, legenda grande, efeitos sonoros.

DADOS
- Link ou arquivo do vídeo: [link do X, link do Google Drive ou arquivo]
- Dono do conteúdo: [nome / @ do criador]
- Autorização: [sim, tenho autorização dele / o vídeo é meu]
- Meu perfil: [@ do TikTok / canal do YouTube]
- Nicho: [ex.: gameplay GTA 6, humor, vendas...]
- Idioma das legendas: português do Brasil

ENTREGAS
1. YouTube (16:9, 1080p): o vídeo completo muito bem editado, estilo aesthetic
   (cor trabalhada, zoom nos momentos fortes, acelerar partes paradas, legenda,
   efeitos sonoros). Se o material tiver 7 min ou mais, faça um compilado de
   7 a 8 minutos com os melhores momentos.
2. TikTok / Shorts (9:16): cortes de [1min10s] com gancho forte nos
   2 primeiros segundos, legenda grande queimada no vídeo e título fixo no topo.
   Quantidade: [de 8 a 10, ou o máximo que o material permitir sem repetir cena].
3. Um arquivo .txt com, para CADA vídeo: 3 opções de título apelativo (mas
   honesto), descrição com crédito ao criador, hashtags, texto da capa,
   comentário para fixar e plano de postagem com horários do Brasil.

REGRAS
- Confirme a autorização antes de baixar ou editar. Sem autorização, não edite
  e me explique como pedir ao dono.
- Dê crédito ao criador original na legenda do vídeo e na descrição.
- Não invente fatos: títulos têm que bater com o que aparece no vídeo.
- Sem música (eu coloco uma em alta pelo app). Use só efeitos sonoros.
- Se o material for curto demais para a quantidade pedida, me diga quantos
  cortes realmente rendem em vez de repetir cenas.
- Antes de entregar, confira quadros de cada vídeo (legenda legível, sem texto
  cortado, áudio sem estourar) e me envie os arquivos .mp4 prontos para baixar.

COMO TRABALHAR
- Veja o vídeo inteiro primeiro (miniaturas a cada 1 ou 2 segundos), anote a
  linha do tempo e só depois defina os cortes.
- Use ffmpeg para: cortes, aceleração, zoom, correção de cor, legenda
  (arquivo .ass com a fonte Anton) e efeitos sonoros. No vertical, deixe o
  vídeo no centro com o fundo desfocado e legenda grande na parte de baixo.
- Contadores de dinheiro, números ou placar animados quando existirem no vídeo.
- Qualidade: YouTube CRF 19, TikTok CRF 20, áudio a -14 LUFS, 1080p.
```

## Avisos para usar em outros chats

- **Links do YouTube não funcionam** no ambiente em nuvem (o YouTube bloqueia o download). Mande o arquivo pelo **Google Drive** ("Qualquer pessoa com o link") ou use um link do **X/Twitter**, que funciona.
- **Só edite conteúdo seu ou com autorização.** Repostar vídeo de outra pessoa sem permissão pode dar strike e derrubar a sua conta.
- **Baixe os arquivos assim que receber.** Ficam numa pasta temporária que pode ser apagada.
- **O chat novo precisa de ferramentas de código** (ffmpeg) para editar de verdade. Em um chat comum, ele só vai te dar o roteiro de cortes. Use este prompt no Claude Code ou em um chat com execução de código.
- **Peça sempre o que quer mudar** depois: cor da legenda, mais ou menos zoom, capa (thumbnail) do YouTube.
