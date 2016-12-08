## How does it work?
1. BDLSTM for conditioning on features (xs)
2. CRF for *local dependence* among labels
3. *Word level* embeddings for `orthographic` features i.e. jargon for structure of word
4. [Lample] (https://arxiv.org/abs/1603.01360)

##Issues
1. Can't handle long term dependencies among labels
  * $y_{t} \Perp y_{t-1} | x{1,..,t} $
