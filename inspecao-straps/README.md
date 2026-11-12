# Inspetor de Straps (piloto)

Página para testar com a câmera do celular a detecção de **elemento invertido**
(par intercélula com dois straps negativos ou dois positivos).

- Feita para rodar como Artifact no Claude (app ou claude.ai): a análise de imagem
  usa a capacidade `sample` (Claude com imagens) e a exportação usa `downloads`.
- Aberta fora do Claude, a página carrega e permite marcar as caixas, mas não analisa.
- A foto de exemplo (`exemplo.jpg`) não está no repositório; sem ela, a página começa vazia.

Fluxo: foto → caixas em pares (1+2, 3+4…) → Analisar → operador confere/corrige →
Salvar → exportar .zip (recortes separados em negativo/positivo + CSVs) para treinar
o modelo local da fase seguinte.
