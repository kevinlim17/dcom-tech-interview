## 임베딩(Embedding)
**사람이 쓰는 자연어를 기계가 이해할 수 있는 숫자의 나열인 벡터로 바꾼 결과 혹은 그 일련의 과정 전체**  


컴퓨터는 기본적으로 숫자로 된 데이터만 처리할 수 있습니다. 
**그렇다면 NLP에서 어떻게 컴퓨터가 자연어를 처리하게 할 수 있을까요?**
이를 위해서는 **사람이 쓰는 자연어를 컴퓨터가 이해할 수 있도록 적절하게 숫자로 변환**을 해주어야 합니다.  
이 일련의 과정 혹은 결과가 바로 **임베딩**입니다.

**품질 좋은 임베딩은 AI의 성능을 끌어올리는데 매우 지대한 영향을 미칩니다.** 따라서 지금도 품질 좋은 임베딩을 만들기 위한 연구가 활발히 진행되고 있습니다.

### 임베딩의 역할
- 단어/문장 간 관련도 계산
- 의미적/문법적 정보 함축
- 전이 학습

### 임베딩의 종류
#### 1. 행렬 분해 기반 방법
말뭉치 정보가 들어 있는 행렬을 두 개 이상의 작은 행렬로 쪼개는 방법입니다.
대표적인 방법으로 Globe와 Swivel이 있습니다.
![matrix](https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile24.uf.tistory.com%2Fimage%2F990F9B405A3923AF21FB8F)  
[이미지 [출처](https://hyeonukdev.github.io/2020/03/30/KoreanEmbedding/%EC%9E%84%EB%B2%A0%EB%94%A9%EA%B8%B0%EB%B2%95%EC%9D%98%EC%97%AD%EC%82%AC%EC%99%80%EC%A2%85%EB%A5%98/)]

#### 2. 예측 기반 방법
어떤 단어 주변에 특정 단어가 나타날지 예측하거나, 이전 단어들이 주어졌을 때 다음 단어가 무엇일지 예측하는 등의 과정으로 학습하는 방법입니다.
대표적인 방법으로 **Word2Vec, FastText, BERT, ELMo, GPT** 등이 있습니다. 

#### 3. 토픽 기반 방법
주어진 문서에 잠재된 주제를 추론하는 방식으로 임베딩을 수행하는 방법입니다.  
대표적인 방법으로 LDA(Latent Dirichlet Allocation)가 있습니다.


## Reference (참고 및 함께보면 좋은 자료)
- 한국어 임베딩 (이기창)