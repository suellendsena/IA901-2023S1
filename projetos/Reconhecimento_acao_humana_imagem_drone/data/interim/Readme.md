## Dados intermediários

Os dados originais, descritos em "raw" e disponíveis em https://drive.google.com/drive/folders/1c-TxV5he38STwtrhZNkPhrAsrB0unwNQ?usp=sharing, são rotulados em diversas classes, conforme descrito no item "Base de Dados e Evolução" (https://github.com/Debora-Simoes/IA901-2023S1/tree/main/projetos/Reconhecimento_acao_humana_imagem_drone#bases-de-dados-e-evolu%C3%A7%C3%A3o). 

A fim de evitar as classes não nomeadas (como "id_" e "block_"), realizou-se uma filtragem nos dados selecionando apenas as classes walk, stand, sit e riding.

Além disso, os dados de treino foram divididos em treino (80%) e validação (20%).

Assim, os dados intermediários estão disponíveis em "Dados_filtrados" (https://drive.google.com/drive/folders/1whsJovK-29ZBCNZhqMQ-Ihot55qsegCe?usp=sharing), que contém 3 pastas:

- Teste (https://drive.google.com/drive/folders/1u_q3b9gPcZeI-Av3sD8FhLE4dFPwCZuR?usp=sharing);
- train (https://drive.google.com/drive/folders/1A9kSON11QiM6fLQlr-FNT6QmQYKES51j?usp=sharing);
- val (https://drive.google.com/drive/folders/1hkKZegYE7iMR1y1z_d3C_k4DD90pSsol?usp=sharing).

A pasta "Dados_filtrados" (anexo) é um subconjunto ilustrativo dos dados intermediários (contém  5 imagens ilustrativas de cada subconjunto), em que se pode visualizar a estrutura em que estão armazenados os dados. Em cada pasta (Teste, train e val), há a pasta "images" e o arquivo "labels_xxx.txt", onde "xxx" é o nome do conjunto (train, val ou test).

Outros dados intermediários do projeto, são os dados obtidos após a filtragem no domínio espacial, adotando o Filtro de Laplace. Conforme pode-se ver na pasta "Filtro_Laplaciano" (anexa), as imagens filtradas são altamente segmentadas e, por isso, o grupo optou por não adotá-las como um conjunto de treinamento. O conjunto completo de imagens obtidas a partir da filtragem laplaciana pode ser verificado em <https://drive.google.com/drive/folders/11fpeEs_bpo2cMhblgVHUovZkou7GaT18?usp=sharing>.
