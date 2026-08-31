# GomsBook AI Interview Q&A 001~300

## 질문 1. 인공지능(AI)이란 무엇인가요?

**답변:** 인간의 인식·추론·학습·의사결정 같은 지능적 작업을 컴퓨터가 수행하도록 하는 기술 분야입니다.

---

## 질문 2. 머신러닝과 딥러닝의 차이는?

**답변:** 머신러닝은 데이터에서 패턴을 학습하는 방법의 총칭이고, 딥러닝은 다층 신경망을 사용하는 머신러닝의 한 분야입니다.

---

## 질문 3. 지도학습·비지도학습·강화학습의 차이는?

**답변:** 지도학습은 Label로 학습하고, 비지도학습은 Label 없이 구조를 찾으며, 강화학습은 환경과 상호작용하며 보상을 최대화합니다.

---

## 질문 4. 신경망이란 무엇인가요?

**답변:** Weight·Bias·Activation을 가진 계산 단위를 여러 층으로 연결하고 Loss를 Backpropagation으로 최소화하는 모델입니다.

---

## 질문 5. Transformer란 무엇인가요?

**답변:** Attention을 중심으로 시퀀스를 처리하여 토큰 관계를 직접 계산하고 병렬 학습에 유리한 신경망 구조입니다.

---

## 질문 6. Self-Attention이란?

**답변:** 같은 시퀀스의 토큰들이 서로의 관련성을 계산해 문맥적 표현을 만드는 방법입니다.

---

## 질문 7. LLM이란 무엇인가요?

**답변:** 대규모 데이터와 파라미터로 언어 패턴을 학습한 모델이며 대표적인 Decoder-only LLM은 다음 Token을 예측하며 생성합니다.

---

## 질문 8. Embedding이란?

**답변:** 텍스트·이미지 등을 의미적 특징을 반영하는 고차원 Vector로 표현하는 방법입니다.

---

## 질문 9. RAG란 무엇인가요?

**답변:** 외부 문서를 검색해 관련 Context를 LLM에 제공한 뒤 근거 기반 답변을 생성하는 Retrieval-Augmented Generation입니다.

---

## 질문 10. AI Agent란 무엇인가요?

**답변:** 목표를 이해하고 LLM 판단을 바탕으로 Tool과 외부 시스템을 선택·실행하는 시스템입니다.

---

## 질문 11. Loss Function이란?

**답변:** 예측과 정답의 차이를 수치화한 함수이며 학습은 일반적으로 이를 최소화합니다.

---

## 질문 12. MSE란?

**답변:** 예측값과 실제값 차이의 제곱 평균으로 MSE=(1/N)Σ(y-ŷ)²입니다.

---

## 질문 13. Cross Entropy란?

**답변:** 실제 정답 분포와 모델 예측 확률분포의 차이를 측정하는 분류용 Loss입니다.

---

## 질문 14. Binary와 Multi-class Classification의 차이는?

**답변:** Binary는 두 클래스, Multi-class는 여러 상호배타적 클래스 중 하나를 예측합니다.

---

## 질문 15. Softmax란?

**답변:** 여러 Logit을 합이 1인 확률분포로 변환하는 함수입니다.

---

## 질문 16. Backpropagation이란?

**답변:** Chain Rule로 Loss에서 각 파라미터까지 Gradient를 역방향으로 계산하는 알고리즘입니다.

---

## 질문 17. Gradient Descent란?

**답변:** Gradient 반대 방향으로 파라미터를 갱신해 Loss를 줄이는 최적화 방법입니다.

---

## 질문 18. SGD와 Mini-batch의 차이는?

**답변:** SGD는 좁은 의미에서 한 샘플, Mini-batch는 작은 데이터 묶음으로 Gradient를 계산합니다.

---

## 질문 19. Adam Optimizer란?

**답변:** Gradient의 1·2차 모멘트 이동평균을 이용해 파라미터별 업데이트를 조정하는 Optimizer입니다.

---

## 질문 20. Fine-tuning이란?

**답변:** 사전학습 모델을 특정 데이터·작업에 맞게 추가 학습하는 과정입니다.

---

## 질문 21. 활성화 함수가 왜 필요한가요?

**답변:** 신경망에 비선형성을 추가해 복잡한 함수를 학습할 수 있게 합니다.

---

## 질문 22. ReLU란?

**답변:** f(x)=max(0,x)이며 계산이 단순하지만 Dying ReLU 문제가 생길 수 있습니다.

---

## 질문 23. Sigmoid의 문제점은?

**답변:** 포화 영역에서 Gradient가 매우 작아져 Vanishing Gradient를 유발할 수 있습니다.

---

## 질문 24. Vanishing Gradient란?

**답변:** 역전파 중 Gradient가 매우 작아져 앞쪽 Layer가 제대로 학습되지 않는 현상입니다.

---

## 질문 25. CNN이란?

**답변:** Convolution으로 지역적·공간적 특징을 추출하는 신경망입니다.

---

## 질문 26. RNN이란?

**답변:** 이전 Hidden State를 다음 시점에 전달하며 순차 데이터를 처리하는 신경망입니다.

---

## 질문 27. LSTM과 RNN의 차이는?

**답변:** LSTM은 Cell State와 Gate로 장기 의존성 문제를 완화합니다.

---

## 질문 28. RNN/LSTM과 Transformer의 차이는?

**답변:** RNN은 순차 처리, Transformer는 Self-Attention으로 토큰 관계를 직접 계산합니다.

---

## 질문 29. Precision과 Recall의 차이는?

**답변:** Precision=TP/(TP+FP), Recall=TP/(TP+FN)입니다.

---

## 질문 30. F1 Score란?

**답변:** Precision과 Recall의 조화평균으로 F1=2PR/(P+R)입니다.

---

## 질문 31. Bias와 Variance란?

**답변:** High Bias는 Underfitting, High Variance는 Overfitting과 연결됩니다.

---

## 질문 32. Regularization이란?

**답변:** Overfitting을 줄여 일반화 성능을 높이는 방법입니다.

---

## 질문 33. L1과 L2의 차이는?

**답변:** L1은 \|w\|로 희소성을, L2는 w²로 큰 Weight 억제를 유도합니다.

---

## 질문 34. Dropout이란?

**답변:** 학습 중 일부 뉴런을 확률적으로 비활성화하는 Regularization입니다.

---

## 질문 35. Batch Normalization이란?

**답변:** Mini-batch 통계로 활성값을 정규화하고 학습 가능한 scale/shift를 적용합니다.

---

## 질문 36. Class Imbalance란?

**답변:** 클래스별 데이터 수가 크게 불균형한 상황으로 Accuracy만으로 평가하면 위험합니다.

---

## 질문 37. ROC/AUC란?

**답변:** ROC는 Threshold별 TPR-FPR 관계, AUC는 ROC 아래 면적입니다.

---

## 질문 38. PCA란?

**답변:** 분산을 최대한 보존하는 직교 축을 찾아 저차원으로 선형 변환하는 방법입니다.

---

## 질문 39. Clustering이란?

**답변:** Label 없이 유사한 데이터를 그룹화하는 비지도학습입니다.

---

## 질문 40. K-means는 어떻게 동작하나요?

**답변:** K개 중심 초기화→가까운 중심에 할당→중심 재계산을 수렴할 때까지 반복합니다.

---

## 질문 41. 확률이란?

**답변:** 사건 발생 가능성을 0\~1 사이 값으로 표현합니다.

---

## 질문 42. 조건부 확률이란?

**답변:** B가 발생한 조건에서 A가 발생할 확률로 P(A\|B)=P(A∩B)/P(B)입니다.

---

## 질문 43. Bayes 정리란?

**답변:** P(A\|B)=P(B\|A)P(A)/P(B)로 사전확률을 증거로 갱신합니다.

---

## 질문 44. 평균·분산·표준편차의 차이는?

**답변:** 평균은 중심, 분산은 제곱 편차 평균, 표준편차는 분산의 제곱근입니다.

---

## 질문 45. 정규분포란?

**답변:** 평균을 중심으로 좌우 대칭인 종 모양의 연속 확률분포입니다.

---

## 질문 46. 공분산이란?

**답변:** 두 변수가 함께 변화하는 방향과 정도를 나타냅니다.

---

## 질문 47. 상관계수와 공분산의 차이는?

**답변:** 상관계수는 공분산을 표준편차로 정규화한 -1\~1 범위의 값입니다.

---

## 질문 48. Vector란?

**답변:** 여러 숫자의 순서 있는 배열이며 AI의 데이터·Embedding 표현에 사용됩니다.

---

## 질문 49. Dot Product란?

**답변:** 대응 원소를 곱해 더하는 연산 A·B=ΣA_iB_i입니다.

---

## 질문 50. Cosine Similarity와 Dot Product의 관계는?

**답변:** cos=(A·B)/(\|\|A\|\|\|\|B\|\|)이며 L2 정규화 Vector에서는 값이 같습니다.

---

## 질문 51. Matrix란?

**답변:** 숫자를 행과 열로 배열한 객체이며 딥러닝 선형변환의 기본 표현입니다.

---

## 질문 52. 행렬 곱셈이란?

**답변:** (m×n)(n×p)→(m×p)이며 각 원소는 행과 열의 Dot Product입니다.

---

## 질문 53. Transpose란?

**답변:** 행과 열을 바꾸는 연산으로 Attention의 QK\^T에 사용됩니다.

---

## 질문 54. Rank란?

**답변:** 행렬의 선형독립 행/열 최대 개수로 독립 정보 차원을 나타냅니다.

---

## 질문 55. Linear Independence란?

**답변:** 어떤 벡터도 다른 벡터들의 선형결합으로 표현되지 않는 상태입니다.

---

## 질문 56. Eigenvalue/Eigenvector란?

**답변:** Av=λv에서 v는 고유벡터, λ는 고유값입니다.

---

## 질문 57. Eigen과 PCA의 관계는?

**답변:** 공분산 행렬의 큰 고유값에 대응하는 고유벡터가 주요 주성분이 됩니다.

---

## 질문 58. SVD란?

**답변:** A=UΣV\^T로 행렬을 분해하는 방법입니다.

---

## 질문 59. Attention에서 QK\^T의 의미는?

**답변:** 각 Query와 Key 사이 Dot Product를 한 번에 계산한 Attention Score 행렬입니다.

---

## 질문 60. Attention 수식을 설명해보세요.

**답변:** softmax(QK\^T/√d_k)V: 관련성 계산→Scaling→Softmax→Value 가중합입니다.

---

## 질문 61. Embedding이란?

**답변:** 비정형 데이터를 의미적 Vector로 표현하는 방법입니다.

---

## 질문 62. Vector Database란?

**답변:** Embedding과 Metadata를 저장하고 유사 Vector를 효율적으로 검색하는 시스템입니다.

---

## 질문 63. Vector Store와 Vector DB는 같은가요?

**답변:** 혼용되지만 DB는 영속성·인덱싱·필터링·확장성까지 강조합니다.

---

## 질문 64. Chunking이 필요한 이유는?

**답변:** 긴 문서를 적절한 단위로 나눠 필요한 부분을 더 정확히 검색하기 위해서입니다.

---

## 질문 65. Chunk Overlap은 왜 사용하나요?

**답변:** Chunk 경계의 문맥 손실을 줄이기 위해 일부 내용을 중복합니다.

---

## 질문 66. Top-K란?

**답변:** 유사도 상위 K개의 검색 결과를 선택하는 것입니다.

---

## 질문 67. RAG 전체 과정은?

**답변:** 문서→Chunk→Embedding→Store, Query→Embedding→Retrieval→Top-K Context→LLM입니다.

---

## 질문 68. Semantic Search와 Keyword Search 차이는?

**답변:** Keyword는 문자열 일치, Semantic은 Embedding 의미 유사성에 강합니다.

---

## 질문 69. Hybrid Search란?

**답변:** Keyword와 Vector Search를 결합해 결과를 융합하는 방식입니다.

---

## 질문 70. Re-ranking이란?

**답변:** 1차 검색 후보를 더 정교한 기준으로 재평가해 순서를 조정합니다.

---

## 질문 71. RAG 성능은 어떻게 평가하나요?

**답변:** Retrieval과 Generation을 분리해 Recall@K/MRR와 Correctness/Faithfulness 등을 봅니다.

---

## 질문 72. Recall@K란?

**답변:** 관련 문서 중 Top-K 안에서 찾아낸 비율입니다.

---

## 질문 73. Precision@K란?

**답변:** Top-K 중 실제 관련 문서의 비율입니다.

---

## 질문 74. MRR이란?

**답변:** 첫 관련 결과의 1/rank를 여러 Query에 대해 평균한 값입니다.

---

## 질문 75. Context Window란?

**답변:** 한 요청에서 모델이 처리할 수 있는 Token 문맥 범위입니다.

---

## 질문 76. Metadata Filtering이란?

**답변:** Vector 유사도와 함께 chapter/file/language 등의 조건으로 검색 범위를 제한합니다.

---

## 질문 77. Query Expansion이란?

**답변:** 원 Query에 관련 표현을 추가해 검색 Recall을 높이는 방법입니다.

---

## 질문 78. Multi-Query Retrieval이란?

**답변:** 질문을 여러 Query로 변환해 검색한 결과를 통합합니다.

---

## 질문 79. RAG와 Fine-tuning 중 무엇을 선택하나요?

**답변:** 외부·최신 지식은 RAG, 모델 행동·작업 적응은 Fine-tuning을 우선 고려합니다.

---

## 질문 80. Agentic RAG란?

**답변:** Agent가 검색 여부·Query 수정·재검색 등을 동적으로 결정하는 RAG입니다.

---

## 질문 81. AI Agent란?

**답변:** 목표에 따라 Tool과 행동을 선택·실행하는 시스템입니다.

---

## 질문 82. Tool Calling이란?

**답변:** LLM이 필요한 외부 기능과 Arguments를 구조화해 호출하도록 하는 방식입니다.

---

## 질문 83. Function Calling과 Tool Calling의 차이는?

**답변:** Function Calling은 함수 호출에 초점, Tool Calling은 검색·API·DB 등 더 넓은 외부 능력을 포함할 수 있습니다.

---

## 질문 84. Agent Loop란?

**답변:** 판단→Action→Tool→Observation→재판단을 반복하는 구조입니다.

---

## 질문 85. Planning이란?

**답변:** 복잡한 목표를 단계로 나누고 실행 순서를 결정하는 과정입니다.

---

## 질문 86. Agent Memory란?

**답변:** 이전 상호작용이나 작업 상태를 이후 판단에 활용하는 메커니즘입니다.

---

## 질문 87. MCP란?

**답변:** AI 애플리케이션이 Tools/Resources/Prompts와 표준 방식으로 연결되는 Model Context Protocol입니다.

---

## 질문 88. Agent와 MCP 차이는?

**답변:** Agent는 판단·실행 로직, MCP는 연결 프로토콜입니다.

---

## 질문 89. RAG와 Agent 차이는?

**답변:** RAG는 지식 검색 패턴, Agent는 행동과 Tool을 결정·실행하는 시스템입니다.

---

## 질문 90. Agentic RAG란?

**답변:** Agent가 Retrieval 과정의 의사결정을 수행하는 구조입니다.

---

## 질문 91. Prompt Engineering이란?

**답변:** 지시·Context·예시·출력 형식을 설계해 모델 행동을 유도합니다.

---

## 질문 92. Zero-shot과 Few-shot 차이는?

**답변:** Zero-shot은 예제 없음, Few-shot은 소수 예제를 제공합니다.

---

## 질문 93. Chain-of-Thought란?

**답변:** 복잡한 문제에서 중간 추론 단계를 활용하는 접근입니다.

---

## 질문 94. Structured Output이란?

**답변:** JSON/Schema 등 미리 정의된 구조로 모델 출력을 제한·검증하는 방식입니다.

---

## 질문 95. Hallucination이란?

**답변:** 근거 없거나 사실과 다른 내용을 그럴듯하게 생성하는 현상입니다.

---

## 질문 96. Guardrail이란?

**답변:** 입력·출력·Tool 실행에 검증·권한·제약을 적용하는 제어 장치입니다.

---

## 질문 97. Human-in-the-loop란?

**답변:** 중요 단계에서 사람이 검토·승인하도록 하는 설계입니다.

---

## 질문 98. LLM은 어떻게 평가하나요?

**답변:** Correctness, Relevance, Faithfulness, Retrieval, Latency, Cost, Tool Success 등을 목적에 맞게 평가합니다.

---

## 질문 99. AI 시스템 재현성이 어려운 이유는?

**답변:** Sampling, 모델 버전, Prompt, Context, 검색 결과 등이 변할 수 있기 때문입니다.

---

## 질문 100. 프로젝트를 AI 연구로 발전시킨다면?

**답변:** EPUB 저작·접근성 자동화에서 RAG/Agent를 적용하고 검색 및 작업 성능을 정량 평가합니다.

---

## 질문 101. RAG 검색이 틀렸는데 LLM이 정답이면 좋은 RAG인가요?

**답변:** 아닙니다. 최종 답이 맞아도 올바른 근거를 찾지 못했다면 Retrieval 관점에서는 실패입니다.

---

## 질문 102. 모든 질문에 RAG를 쓰면 더 좋나요?

**답변:** 아닙니다. 불필요한 검색은 비용·Latency·Noise를 늘릴 수 있습니다.

---

## 질문 103. Agent가 꼭 필요한가요?

**답변:** 아닙니다. 결정론적 절차는 Workflow가 적합하고 동적 Tool 선택이 필요한 부분에 Agent가 유용합니다.

---

## 질문 104. EPUB Validator가 있는데 왜 LLM이 필요한가요?

**답변:** 규칙 기반 검사는 구조적 오류에, LLM/Vision은 ALT 품질 같은 의미적 판단에 강해 Hybrid 구성이 가능합니다.

---

## 질문 105. LLM이 Validator보다 더 좋은가요?

**답변:** 항상 그렇지 않습니다. 명확한 규칙은 결정론적 Validator가 더 정확하고 재현 가능합니다.

---

## 질문 106. LLM이 잘못된 ALT를 생성하면?

**답변:** Prompt 제약, Validation, Rule Check, Human Review 후 적용해야 합니다.

---

## 질문 107. Embedding 모델을 바꾸면 검색 결과도 달라지나요?

**답변:** 네. 표현 공간이 달라 동일 Query라도 Retrieval 성능이 달라질 수 있습니다.

---

## 질문 108. Chunk Size는 어떻게 결정하나요?

**답변:** 여러 크기와 Overlap을 동일 Dataset에서 Recall@K/MRR/답변 품질로 비교해 결정합니다.

---

## 질문 109. 왜 EPUB RAG인가요?

**답변:** EPUB은 XHTML 구조·Metadata·이미지·접근성 속성을 Retrieval에 활용할 수 있는 구조화 문서입니다.

---

## 질문 110. 석사 연구의 핵심 가설은?

**답변:** EPUB 구조·Metadata를 활용한 RAG/Agent가 일반 Text Retrieval보다 저작·접근성 작업 성능을 높이는지 검증합니다.

---

## 질문 111. 왜 MCP를 직접 구현했나요?

**답변:** 프로토콜 내부 구조와 Agent-Tool 분리를 이해하기 위한 엔지니어링 기반 작업입니다.

---

## 질문 112. MCP 없이도 Tool Calling이 가능한데 왜 필요한가요?

**답변:** 가능하지만 MCP는 외부 AI 시스템과 Tool/Context를 표준 인터페이스로 연결합니다.

---

## 질문 113. RAG에 Vector DB가 반드시 필요한가요?

**답변:** 아닙니다. 소규모에서는 InMemory VectorStore와 Exact Search도 충분합니다.

---

## 질문 114. Vector가 수백만 개라면 모두 비교하나요?

**답변:** 대규모에서는 HNSW/IVF 같은 ANN을 사용해 속도와 Recall의 Trade-off를 관리합니다.

---

## 질문 115. Agent Tool 선택 정확도는 어떻게 평가하나요?

**답변:** 기대 Tool이 정의된 Dataset으로 Tool Selection Accuracy를 측정하고 Argument/Task Success도 평가합니다.

---

## 질문 116. Tool은 맞지만 Argument가 틀리면 성공인가요?

**답변:** 아닙니다. Selection, Argument, Validation, Execution, End-to-End Success를 분리해 봐야 합니다.

---

## 질문 117. LLM-as-a-Judge는 신뢰할 수 있나요?

**답변:** 유용하지만 Bias가 있어 Automatic Metrics와 Human Evaluation을 함께 사용하는 것이 좋습니다.

---

## 질문 118. Baseline이 왜 중요하나요?

**답변:** 제안 방법의 효과를 객관적으로 판단할 비교 기준이기 때문입니다.

---

## 질문 119. EPUB RAG Baseline은?

**답변:** Keyword→Basic Vector RAG→Vector+Metadata→Structure-aware RAG처럼 단계적으로 비교할 수 있습니다.

---

## 질문 120. GomsBook에서 연구 가치가 높은 부분은?

**답변:** EPUB 구조·접근성 정보를 활용한 Structure-aware RAG와 Agent 결합을 정량 검증하는 부분입니다.

---

## 질문 121. 왜 AI 대학원에 진학하려고 하나요?

**답변:** 구현 경험을 이론적 이해와 정량적 연구로 발전시키고 AI 기반을 체계적으로 학습하기 위해서입니다.

---

## 질문 122. 왜 지금 AI 분야로 전환하려고 하나요?

**답변:** 기존 소프트웨어 경험에 AI를 결합해 지능형 애플리케이션 설계 역량으로 확장하기 위해서입니다.

---

## 질문 123. AI 연구 경험이 부족한데 가능한가요?

**답변:** 구현 경험을 Evaluation Dataset, Baseline, Recall@K/MRR/F1 같은 정량 평가로 연결해 보완할 수 있습니다.

---

## 질문 124. 연구 주제는 어떻게 선정하나요?

**답변:** 기술 나열이 아니라 해결할 문제와 검증 가능한 Research Question에서 출발합니다.

---

## 질문 125. 가설이란?

**답변:** 연구를 통해 검증할 수 있도록 구체화한 예상 또는 주장입니다.

---

## 질문 126. 실험 설계에서 중요한 것은?

**답변:** 비교 변수 외 조건을 통제해 성능 차이의 원인을 해석할 수 있게 하는 것입니다.

---

## 질문 127. Ablation Study란?

**답변:** 구성 요소를 제거·변경하며 각 요소의 성능 기여도를 분석하는 실험입니다.

---

## 질문 128. 재현성은 왜 중요하나요?

**답변:** 다른 연구자가 유사 조건에서 결과를 반복·검증할 수 있어야 신뢰성이 높아집니다.

---

## 질문 129. 예상과 다른 결과면 연구 실패인가요?

**답변:** 아닙니다. 가설이 지지되지 않은 결과도 연구 결과이며 원인 분석이 중요합니다.

---

## 질문 130. 석사 논문의 기여는?

**답변:** EPUB Structure-aware Retrieval과 Agent 기반 접근성 자동화를 설계하고 Baseline 대비 개선을 정량 검증하는 것입니다.

---

## 질문 131. LLM Pre-training이란?

**답변:** 대규모 데이터에서 일반 언어 패턴을 학습하는 단계이며 Decoder-only 모델은 주로 다음 Token을 예측합니다.

---

## 질문 132. SFT란?

**답변:** 입력-목표 출력 쌍으로 사전학습 모델을 지시 수행에 맞게 추가 학습하는 Supervised Fine-Tuning입니다.

---

## 질문 133. RLHF란?

**답변:** 인간 선호 피드백을 이용해 모델 응답을 정렬하는 Reinforcement Learning 접근입니다.

---

## 질문 134. DPO란?

**답변:** Chosen/Rejected preference pair를 이용해 별도 Reward Model·전통적 RL 없이 직접 최적화하는 방법입니다.

---

## 질문 135. LoRA란?

**답변:** 저랭크 행렬로 Weight 변화량을 학습해 학습 파라미터 수를 줄이는 PEFT 기법입니다.

---

## 질문 136. PEFT란?

**답변:** 전체가 아닌 일부/추가 파라미터만 학습해 모델을 효율적으로 적응시키는 방법군입니다.

---

## 질문 137. Quantization이란?

**답변:** Weight/Activation의 수치 정밀도를 낮춰 메모리·연산 비용을 줄이는 방법입니다.

---

## 질문 138. LoRA와 Quantization 차이는?

**답변:** LoRA는 효율적 학습, Quantization은 수치 표현 경량화입니다. QLoRA는 둘을 결합합니다.

---

## 질문 139. KV Cache란?

**답변:** 이전 Token의 Key/Value를 저장·재사용해 Autoregressive 생성의 중복 계산을 줄입니다.

---

## 질문 140. Local LLM과 Cloud LLM 선택 기준은?

**답변:** 데이터 통제, 오프라인, 인프라, 성능, 비용, 운영 편의를 기준으로 선택합니다.

---

## 질문 141. Tokenization이란?

**답변:** 문자열을 Token으로 분해하고 Token ID로 변환하는 과정입니다.

---

## 질문 142. BPE란?

**답변:** 빈도가 높은 문자/심볼 조합을 반복 병합하는 Subword Tokenization 방식입니다.

---

## 질문 143. Vocabulary란?

**답변:** Tokenizer가 사용할 수 있는 Token 집합입니다.

---

## 질문 144. Logit이란?

**답변:** Softmax 전 각 Token/Class 후보에 대한 정규화되지 않은 점수입니다.

---

## 질문 145. Greedy Decoding이란?

**답변:** 각 단계에서 가장 높은 점수의 Token 하나를 선택합니다.

---

## 질문 146. Top-K Sampling이란?

**답변:** 상위 K개 Token만 후보로 남겨 Sampling합니다.

---

## 질문 147. Top-P Sampling이란?

**답변:** 누적 확률이 P에 도달하는 후보 집합에서 Sampling하는 Nucleus Sampling입니다.

---

## 질문 148. Temperature는 어떻게 적용되나요?

**답변:** Softmax 전에 Logit을 T로 나누며 낮을수록 분포가 날카롭고 높을수록 평평해집니다.

---

## 질문 149. Perplexity란?

**답변:** 언어모델의 다음 Token 예측 불확실성 지표로 PPL=e\^L로 표현할 수 있습니다.

---

## 질문 150. MoE란?

**답변:** Router가 여러 Expert 중 Token별 일부만 선택해 처리하는 Mixture of Experts 구조입니다.

---

## 질문 151. 미분과 Gradient란?

**답변:** 미분은 변화율, Gradient는 다변수 함수의 편미분을 모은 벡터입니다.

---

## 질문 152. Chain Rule이란?

**답변:** 합성함수 미분 법칙이며 Backpropagation의 핵심입니다.

---

## 질문 153. 편미분이란?

**답변:** 다른 변수는 상수로 두고 특정 변수 하나에 대해 미분합니다.

---

## 질문 154. Gradient Descent 계산 예시는?

**답변:** L=w²,w=4,η=0.1이면 gradient=8, w_new=3.2입니다.

---

## 질문 155. Softmax 계산 예시는?

**답변:** z=\[2,1,0\]이면 약 \[0.665,0.245,0.090\]입니다.

---

## 질문 156. Cross Entropy 계산 예시는?

**답변:** 정답 Class 확률이 0.665이면 L=-log(0.665)≈0.408입니다.

---

## 질문 157. Cosine Similarity 계산 예시는?

**답변:** A=(1,2),B=(2,1)이면 dot=4, norm은 각각 √5, cosine=0.8입니다.

---

## 질문 158. 행렬 곱셈 차원은?

**답변:** 3×4와 4×5의 곱은 3×5입니다.

---

## 질문 159. Attention 행렬 크기는?

**답변:** Q=10×64,K\^T=64×10이면 QK\^T=10×10입니다.

---

## 질문 160. Scaled Dot-Product Attention 계산 예시는?

**답변:** 동일 score의 두 Value에 weight 0.5씩이면 V1=\[2,0\],V2=\[0,4\]의 출력은 \[1,2\]입니다.

---

## 질문 161. Sigmoid 미분은?

**답변:** σ'(x)=σ(x)(1-σ(x)); x=0에서는 0.25입니다.

---

## 질문 162. ReLU 미분은?

**답변:** x\<0에서 0, x\>0에서 1이며 x=0은 미분 불가능해 구현상 subgradient를 정합니다.

---

## 질문 163. Softmax+Cross Entropy Gradient는?

**답변:** Logit에 대한 Gradient가 p-y로 단순화됩니다.

---

## 질문 164. MSE 계산 예시는?

**답변:** y=\[3,5,2\],ŷ=\[2,4,4\]이면 MSE=(1+1+4)/3=2입니다.

---

## 질문 165. 평균과 분산 계산 예시는?

**답변:** \[2,4,6,8\]의 평균=5, 모집단 분산=5, 표준편차=√5입니다.

---

## 질문 166. Z-score 계산 예시는?

**답변:** μ=50,σ=10,x=70이면 z=2입니다.

---

## 질문 167. Bayes 계산 예시는?

**답변:** P(E)=0.1,P(D\|E)=0.9,P(D\|N)=0.05이면 P(E\|D)=0.09/0.135≈0.667입니다.

---

## 질문 168. 조건부확률 계산 예시는?

**답변:** ALT 오류 20개 중 장식 이미지 5개면 P(Decorative\|AltError)=0.25입니다.

---

## 질문 169. Precision/Recall/F1 계산 예시는?

**답변:** TP=80,FP=20,FN=40이면 P=0.8,R≈0.667,F1≈0.727입니다.

---

## 질문 170. PCA를 간단히 계산하면?

**답변:** (1,1),(2,2),(3,3),(4,4)는 (1,1) 방향에 분산이 집중되어 1차원으로 축소 가능합니다.

---

## 질문 171. Linear Regression 기본 식은?

**답변:** ŷ=wx+b, 다변수에서는 ŷ=XW+b입니다.

---

## 질문 172. Linear Regression Gradient 예시는?

**답변:** L=(y-wx)², x=2,y=10,w=3이면 gradient=-16, η=0.1이면 w_new=4.6입니다.

---

## 질문 173. Logistic Regression은 무엇이 다른가요?

**답변:** 선형결합을 Sigmoid에 통과시켜 0\~1 확률을 출력합니다.

---

## 질문 174. Binary Cross Entropy 계산은?

**답변:** y=1,p=0.8이면 BCE=-log(0.8)≈0.223입니다.

---

## 질문 175. L2 Regularization 계산은?

**답변:** Loss=2,w=\[1,2,3\],λ=0.1이면 penalty=1.4,total=3.4입니다.

---

## 질문 176. L1 Regularization 계산은?

**답변:** 같은 조건이면 penalty=0.6,total=2.6입니다.

---

## 질문 177. Attention Mask란?

**답변:** 특정 Token 위치를 Attention에서 참조하지 못하게 제한합니다.

---

## 질문 178. Causal Mask란?

**답변:** 현재 Token이 미래 Token을 보지 못하게 하는 Decoder용 Mask입니다.

---

## 질문 179. Multi-Head Attention 차원 계산은?

**답변:** d_model=512,h=8이면 head당 64차원이고 concatenate 후 512차원입니다.

---

## 질문 180. QKV Projection Parameter 수는?

**답변:** d_model=512이면 QKV는 3×512²=786,432개, Output까지 4×512²=1,048,576개입니다.

---

## 질문 181. Transformer Block의 주요 구성은?

**답변:** Multi-Head Attention, Residual Connection, LayerNorm, FFN이 핵심입니다.

---

## 질문 182. FFN이란?

**답변:** 각 Token 위치에 독립적으로 적용되는 MLP로 보통 d_model→d_ff→d_model 구조입니다.

---

## 질문 183. FFN Parameter 수 계산은?

**답변:** d_model=512,d_ff=2048이면 두 Weight 합은 2×512×2048=2,097,152개입니다.

---

## 질문 184. 왜 FFN 중간 차원을 크게 잡나요?

**답변:** 더 높은 차원의 비선형 공간에서 풍부한 feature transformation을 수행한 뒤 다시 투영하기 위해서입니다.

---

## 질문 185. Residual Connection은 왜 사용하나요?

**답변:** x+F(x)로 정보와 Gradient 흐름을 개선해 깊은 네트워크 학습을 안정화합니다.

---

## 질문 186. Pre-LN과 Post-LN 차이는?

**답변:** Pre-LN은 Sublayer 전, Post-LN은 Residual 결합 후 LayerNorm을 적용합니다.

---

## 질문 187. Transformer Encoder와 Decoder 차이는?

**답변:** Encoder는 입력 전체를 표현하고 Autoregressive Decoder는 Causal Mask로 미래 Token을 차단하며 생성합니다.

---

## 질문 188. Cross-Attention이란?

**답변:** Query는 한 시퀀스에서, Key/Value는 다른 시퀀스에서 가져와 두 정보원을 연결하는 Attention입니다.

---

## 질문 189. Beam Search란?

**답변:** 누적 점수가 높은 여러 후보 시퀀스를 유지하며 탐색하는 Decoding 방법입니다.

---

## 질문 190. BLEU와 ROUGE 및 한계는?

**답변:** BLEU는 주로 n-gram precision, ROUGE는 overlap/recall 기반입니다. 의미가 같아도 표현이 다르면 낮게 평가할 수 있어 LLM 평가에는 다른 지표와 Human Evaluation을 병행합니다.

---

## 질문 191. Position Encoding이 필요한 이유는 무엇인가요?

**답변:** Transformer에는 순환 구조가 없으므로 토큰의 순서를 별도로 표현해야 합니다. Position Encoding을 입력 표현에 추가해 위치 정보를 제공합니다.

---

## 질문 192. Sinusoidal Positional Encoding이란 무엇인가요?

**답변:** 위치별 sine/cosine 함수를 사용해 학습 파라미터 없이 위치 정보를 만드는 방식입니다.

---

## 질문 193. RoPE(Rotary Position Embedding)란 무엇인가요?

**답변:** Query와 Key 표현을 위치에 따라 회전시켜 상대적 위치 관계를 Attention에 반영하는 위치 인코딩 방식입니다.

---

## 질문 194. Context Length가 길어질 때 어떤 문제가 생기나요?

**답변:** Attention 계산량과 KV Cache 메모리가 증가하고, 긴 문맥에서 중요한 정보를 안정적으로 검색·활용하는 문제도 커집니다.

---

## 질문 195. FlashAttention이란 무엇인가요?

**답변:** Attention 계산을 메모리 효율적으로 재구성해 정확한 Attention 결과를 유지하면서 메모리 접근 비용과 실행 시간을 줄이는 기법입니다.

---

## 질문 196. Grouped-Query Attention(GQA)이란 무엇인가요?

**답변:** 여러 Query Head가 Key/Value Head를 그룹 단위로 공유해 MHA의 품질과 MQA의 효율 사이를 절충합니다.

---

## 질문 197. Multi-Query Attention(MQA)이란 무엇인가요?

**답변:** 여러 Query Head가 하나의 Key/Value Head를 공유해 KV Cache와 추론 비용을 줄이는 방식입니다.

---

## 질문 198. Encoder-only, Decoder-only, Encoder-Decoder 모델의 차이는?

**답변:** Encoder-only는 이해·표현, Decoder-only는 자기회귀 생성, Encoder-Decoder는 입력 인코딩 후 조건부 생성을 중심으로 설계됩니다.

---

## 질문 199. BERT와 GPT의 학습 방식 차이는?

**답변:** BERT는 주로 Masked Language Modeling으로 양방향 문맥을 학습하고 GPT는 다음 Token 예측 방식으로 자기회귀 학습합니다.

---

## 질문 200. Transformer의 시간·공간 복잡도에서 Attention의 병목은 무엇인가요?

**답변:** 표준 Self-Attention은 시퀀스 길이 n에 대해 Attention Score 행렬이 n×n이어서 계산·메모리 비용이 대체로 O(n²)로 증가합니다.

---

## 질문 201. RAG에서 Chunk Size가 너무 작거나 크면 어떤 문제가 생기나요?

**답변:** 너무 작으면 문맥이 끊기고 너무 크면 관련 없는 정보가 섞여 Retrieval 정밀도가 떨어질 수 있습니다.

---

## 질문 202. Parent-Child Chunking이란 무엇인가요?

**답변:** 작은 Child Chunk로 검색하고 더 넓은 Parent Chunk를 Context로 확장해 검색 정밀도와 문맥 보존을 함께 노리는 방법입니다.

---

## 질문 203. Structure-aware Chunking이란 무엇인가요?

**답변:** 문서를 고정 길이만으로 자르지 않고 제목·절·XHTML 구조·Metadata 같은 문서 구조를 활용해 Chunk를 만드는 방법입니다.

---

## 질문 204. Dense Retrieval과 Sparse Retrieval의 차이는?

**답변:** Dense Retrieval은 Embedding 의미 유사도를, Sparse Retrieval은 단어 빈도와 희소 표현을 중심으로 검색합니다.

---

## 질문 205. BM25란 무엇인가요?

**답변:** Query와 문서의 단어 빈도, 문서 빈도, 문서 길이를 반영하는 대표적인 Sparse Retrieval 랭킹 함수입니다.

---

## 질문 206. ANN(Approximate Nearest Neighbor)이란 무엇인가요?

**답변:** 모든 Vector를 정확히 비교하는 대신 가까운 이웃을 빠르게 근사 탐색해 대규모 Vector 검색을 가속하는 방법입니다.

---

## 질문 207. HNSW란 무엇인가요?

**답변:** 계층적 그래프를 구성해 가까운 Vector를 탐색하는 대표적인 ANN 인덱스입니다.

---

## 질문 208. Retrieval Threshold는 왜 필요한가요?

**답변:** 유사도가 너무 낮은 결과를 Context에서 제외해 무관한 문서가 LLM에 전달되는 것을 줄이기 위해 사용합니다.

---

## 질문 209. Reranker는 Retriever와 어떻게 다른가요?

**답변:** Retriever는 후보를 빠르게 찾고 Reranker는 그 후보를 더 정교한 모델이나 기준으로 재평가해 순서를 조정합니다.

---

## 질문 210. Cross-Encoder Reranking이란 무엇인가요?

**답변:** Query와 각 후보 문서를 함께 모델에 입력해 관련성을 직접 점수화하는 Reranking 방식으로, 보통 Bi-Encoder 검색보다 정교하지만 비용이 큽니다.

---

## 질문 211. RAG에서 Context Precision이란 무엇인가요?

**답변:** 검색된 Context 중 실제 질문에 관련된 Context가 얼마나 상위에 잘 배치됐는지를 평가하는 관점의 지표입니다.

---

## 질문 212. RAG에서 Context Recall이란 무엇인가요?

**답변:** 정답을 생성하는 데 필요한 근거가 검색 Context에 얼마나 충분히 포함됐는지를 평가합니다.

---

## 질문 213. Faithfulness란 무엇인가요?

**답변:** 생성 답변의 주장들이 제공된 Context에 의해 얼마나 뒷받침되는지를 평가하는 개념입니다.

---

## 질문 214. Answer Relevancy란 무엇인가요?

**답변:** 생성 답변이 사용자의 질문에 얼마나 직접적이고 관련 있게 답하는지를 평가합니다.

---

## 질문 215. RAGAS란 무엇인가요?

**답변:** RAG 시스템의 Context와 Answer 품질을 Faithfulness, Answer Relevancy, Context Precision/Recall 등의 관점으로 평가하는 프레임워크입니다.

---

## 질문 216. Golden Dataset이란 무엇인가요?

**답변:** 평가용 질문, 기대 답변, 관련 근거 등을 사람이 검증해 만든 기준 Dataset입니다.

---

## 질문 217. RAG 평가에서 No-Answer Case가 필요한 이유는?

**답변:** 근거가 없는 질문에 억지 답변을 생성하지 않는 능력을 평가해야 Hallucination과 과잉 검색을 확인할 수 있습니다.

---

## 질문 218. RAG Regression Test란 무엇인가요?

**답변:** Retriever, Embedding, Prompt 등의 변경 후 기존 평가 Dataset의 성능이 악화되지 않았는지 자동 비교하는 테스트입니다.

---

## 질문 219. Embedding 모델 변경 시 무엇을 다시 평가해야 하나요?

**답변:** 동일 Dataset으로 Recall@K, MRR, Context Precision/Recall과 최종 답변 품질을 다시 측정하고 기존 Baseline과 비교해야 합니다.

---

## 질문 220. GomsBook의 RAG 성능을 어떻게 실험적으로 검증할 수 있나요?

**답변:** 고정 Golden Dataset과 Baseline을 만들고 Chunking, Embedding, Top-K, Reranking 등의 변수를 통제해 Retrieval과 Generation 지표를 비교합니다.

---

## 질문 221. AI Agent의 Tool Registry란 무엇인가요?

**답변:** Agent가 사용할 수 있는 Tool의 이름, 설명, Schema, 실행 구현을 등록하고 조회하는 구성 요소입니다.

---

## 질문 222. Tool Executor의 역할은 무엇인가요?

**답변:** 선택된 Tool과 Arguments를 검증하고 실제 기능을 호출한 뒤 성공·오류 결과를 Agent에 반환하는 실행 계층입니다.

---

## 질문 223. Agent Context란 무엇인가요?

**답변:** 현재 Run의 프로젝트, 사용자 요청, 설정, 상태 등 Tool 실행에 필요한 공통 실행 문맥입니다.

---

## 질문 224. Tool 실행 결과를 구조화해야 하는 이유는 무엇인가요?

**답변:** LLM과 UI가 성공·실패·데이터·오류를 일관되게 처리하고 자동 평가와 재시도를 가능하게 하기 위해서입니다.

---

## 질문 225. Agent에서 Plan과 Execution을 분리하는 이유는 무엇인가요?

**답변:** 계획과 실제 부작용이 있는 실행을 분리하면 검토·승인·재시도·관찰 가능성을 높일 수 있습니다.

---

## 질문 226. Sequential Execution과 Parallel Execution의 차이는?

**답변:** Sequential은 선행 결과에 의존해 순서대로 실행하고 Parallel은 서로 독립적인 작업을 동시에 실행해 지연시간을 줄입니다.

---

## 질문 227. Agent에서 Retry 정책은 어떻게 설계하나요?

**답변:** 일시적 오류에만 제한된 횟수와 Backoff를 적용하고, 비멱등 작업의 중복 실행을 방지하며 최종 실패를 명확히 반환해야 합니다.

---

## 질문 228. Agent에서 Timeout이 필요한 이유는?

**답변:** 외부 Tool이나 모델이 무한 대기해 전체 Run을 점유하지 않도록 실행 시간의 상한을 두기 위해 필요합니다.

---

## 질문 229. Idempotency란 무엇이며 Tool 실행에서 왜 중요한가요?

**답변:** 같은 요청을 여러 번 실행해도 결과나 시스템 상태가 의도치 않게 중복 변경되지 않는 성질이며 Retry 안전성과 관련됩니다.

---

## 질문 230. Agent의 상태(State)는 어떻게 관리하나요?

**답변:** Run ID를 기준으로 계획, 이벤트, Tool 결과, 승인 상태 등을 명시적으로 관리하고 필요한 경우 영속 저장소에 보존합니다.

---

## 질문 231. Human Approval이 필요한 Tool은 어떤 것인가요?

**답변:** 파일 삭제·덮어쓰기, 외부 전송, 결제처럼 되돌리기 어렵거나 권한·보안 영향이 큰 작업에 사람 승인을 두는 것이 적절합니다.

---

## 질문 232. Approval Required 이벤트는 어떻게 설계할 수 있나요?

**답변:** Run을 일시 중지하고 approvalId, 대상 작업, Arguments를 포함한 APPROVAL_REQUIRED 이벤트를 전달한 뒤 approve/reject 결과로 재개합니다.

---

## 질문 233. Agent 실행에서 Event Streaming을 사용하는 이유는?

**답변:** Planning, Tool Call, Approval, Result 같은 장시간 실행 중간 상태를 클라이언트에 실시간 전달하기 위해 사용합니다.

---

## 질문 234. SSE(Server-Sent Events)란 무엇인가요?

**답변:** HTTP 연결을 유지하면서 서버가 클라이언트에 단방향 이벤트 스트림을 지속적으로 전송하는 방식입니다.

---

## 질문 235. SSE와 WebSocket의 차이는 무엇인가요?

**답변:** SSE는 서버→클라이언트 단방향 스트리밍에 단순하고, WebSocket은 하나의 연결에서 양방향 실시간 통신을 제공합니다.

---

## 질문 236. Agent Observability란 무엇인가요?

**답변:** Agent의 계획, Tool 호출, 지연시간, 오류, Token/비용, 결과를 추적해 실행을 설명하고 문제를 진단할 수 있게 하는 능력입니다.

---

## 질문 237. Trace와 Log의 차이는 무엇인가요?

**답변:** Log는 개별 기록이고 Trace는 하나의 요청이 여러 구성 요소를 통과하는 전체 실행 흐름을 상관관계로 연결합니다.

---

## 질문 238. Agent 실행 평가에서 Task Success Rate란 무엇인가요?

**답변:** 주어진 Task가 최종 목표를 올바르게 완료한 비율입니다.

---

## 질문 239. Agent Tool Selection Accuracy란 무엇인가요?

**답변:** 평가 Dataset에서 기대한 Tool과 Agent가 실제 선택한 Tool이 일치하는 비율입니다.

---

## 질문 240. Agent의 End-to-End Evaluation이 필요한 이유는 무엇인가요?

**답변:** Tool 선택만 맞아도 최종 결과가 실패할 수 있으므로 계획부터 Arguments, 실행, 결과까지 전체 Task 성공을 평가해야 합니다.

---

## 질문 241. MCP에서 Tool, Resource, Prompt의 역할 차이는 무엇인가요?

**답변:** Tool은 실행 가능한 기능, Resource는 읽을 Context/데이터, Prompt는 재사용 가능한 프롬프트 템플릿 역할을 합니다.

---

## 질문 242. MCP Server와 Client의 역할은 무엇인가요?

**답변:** Server는 Tool/Resource/Prompt를 제공하고 Client는 이를 발견하고 호출해 AI 애플리케이션과 연결합니다.

---

## 질문 243. MCP에서 JSON-RPC를 사용하는 이유는 무엇인가요?

**답변:** 요청 ID, method, params, result/error 구조를 갖춘 표준 RPC 메시지로 기능 호출과 응답을 일관되게 표현할 수 있기 때문입니다.

---

## 질문 244. MCP의 Tool Discovery란 무엇인가요?

**답변:** Client가 Server가 제공하는 Tool 목록과 Schema를 조회해 사용 가능한 기능을 동적으로 파악하는 과정입니다.

---

## 질문 245. MCP에서 입력 Schema가 중요한 이유는 무엇인가요?

**답변:** LLM이 올바른 Arguments를 생성하고 Server가 입력을 검증할 수 있는 명확한 계약이 되기 때문입니다.

---

## 질문 246. MCP Tool 실행 오류는 어떻게 표현해야 하나요?

**답변:** 프로토콜 수준 오류와 Tool 실행 결과의 실패를 구분하고 구조화된 error code/message와 필요한 세부 정보를 반환해야 합니다.

---

## 질문 247. MCP와 REST API의 차이는 무엇인가요?

**답변:** REST는 일반적인 웹 Resource/API 설계 방식이고 MCP는 AI 애플리케이션이 Tool·Resource·Prompt를 발견하고 사용하는 표준 Context 연결에 초점을 둡니다.

---

## 질문 248. MCP를 Agent Architecture에 적용할 때 장점은 무엇인가요?

**답변:** Agent의 판단 계층과 외부 기능 제공 계층을 분리하고 표준 인터페이스로 다양한 Tool Server를 교체·확장하기 쉬워집니다.

---

## 질문 249. 외부 MCP Server를 사용할 때 보안상 무엇을 확인해야 하나요?

**답변:** Server 신뢰성, 권한 범위, 입력 검증, 데이터 유출, Prompt Injection, Tool 부작용, 인증·감사 로그를 확인해야 합니다.

---

## 질문 250. GomsBook AI에서 MCP를 적용한 이유를 설명해보세요.

**답변:** EPUB 관련 Tool을 Agent 실행 로직과 분리하고 향후 외부 AI Client에서도 동일 기능을 표준 방식으로 사용할 수 있도록 하기 위해 적용했습니다.

---

## 질문 251. AI Agent와 Workflow의 차이는 무엇인가요?

**답변:** Workflow는 미리 정의된 절차를 실행하는 구조이고 Agent는 목표와 상황에 따라 다음 행동과 Tool을 동적으로 선택합니다.

---

## 질문 252. Deterministic Workflow란 무엇인가요?

**답변:** 조건과 실행 순서가 코드·규칙으로 명확히 정의되어 동일 입력에 예측 가능한 흐름을 수행하는 Workflow입니다.

---

## 질문 253. Agentic Workflow란 무엇인가요?

**답변:** LLM이나 Agent가 상황에 따라 단계, Tool, 분기 등을 동적으로 결정하는 Workflow입니다.

---

## 질문 254. Orchestration이란 무엇인가요?

**답변:** 여러 Agent, Tool, Workflow의 실행 순서·의존성·상태를 조정해 전체 작업을 완수하도록 관리하는 것입니다.

---

## 질문 255. Multi-Agent 시스템이란 무엇인가요?

**답변:** 역할이 다른 여러 Agent가 협력·분업해 하나의 복잡한 목표를 해결하는 시스템입니다.

---

## 질문 256. Agent 간 Communication은 어떻게 이루어지나요?

**답변:** 구조화된 Message, 공유 State, Event, Queue 또는 Supervisor를 통해 목표·결과·상태를 전달할 수 있습니다.

---

## 질문 257. Supervisor Agent란 무엇인가요?

**답변:** 여러 Worker Agent의 작업을 분배하고 결과를 통합하며 다음 실행을 조정하는 상위 Agent입니다.

---

## 질문 258. Agent Security에서 고려해야 할 핵심 요소는 무엇인가요?

**답변:** 최소 권한, Tool allowlist, 입력·출력 검증, 승인, 비밀정보 보호, 격리, 감사 로그, Prompt Injection 방어가 핵심입니다.

---

## 질문 259. Prompt Injection이란 무엇인가요?

**답변:** 공격자가 입력이나 외부 문서에 악성 지시를 넣어 모델이 원래 지시를 무시하거나 허용되지 않은 행동을 하도록 유도하는 공격입니다.

---

## 질문 260. RAG Prompt Injection이란 무엇이며 어떻게 방어하나요?

**답변:** 검색 문서에 악성 지시를 삽입해 Agent/LLM을 조작하는 공격입니다. 검색 Context를 데이터로 취급하고 권한 분리, Tool 검증, allowlist, 승인, 출처 검증을 적용해야 합니다.

---

## 질문 261. 연구 문제(Research Problem)는 어떻게 정의하나요?

**답변:** 넓은 관심사를 측정·검증 가능한 구체적 질문으로 좁히고 대상, 변수, 평가 기준과 연구 범위를 명확히 정의합니다.

---

## 질문 262. Hypothesis란 무엇이며 좋은 가설의 조건은 무엇인가요?

**답변:** 가설은 변수 간 예상 관계에 대한 검증 가능한 주장입니다. 구체적이고 반증 가능하며 측정 가능한 형태가 좋습니다.

---

## 질문 263. Baseline이란 무엇이며 왜 필요한가요?

**답변:** 제안 방법의 개선 여부를 판단하기 위한 비교 기준 모델·방법입니다. Baseline이 있어야 효과의 크기와 원인을 해석할 수 있습니다.

---

## 질문 264. Experimental Design이란 무엇인가요?

**답변:** 가설을 검증하도록 Dataset, 비교군, 변수, Metric, 반복 조건과 분석 절차를 체계적으로 설계하는 것입니다.

---

## 질문 265. Independent Variable과 Dependent Variable의 차이는 무엇인가요?

**답변:** Independent Variable은 연구자가 변경·통제하는 원인 변수이고 Dependent Variable은 그 변화에 따라 측정하는 결과 변수입니다.

---

## 질문 266. Ablation Study란 무엇인가요?

**답변:** 시스템 구성 요소를 하나씩 제거하거나 변경해 각 요소가 성능 향상에 얼마나 기여하는지 분석하는 실험입니다.

---

## 질문 267. Statistical Significance란 무엇인가요?

**답변:** 관측된 차이가 우연만으로 발생했다고 보기 어려운지를 통계적으로 판단하는 개념이며 p-value, confidence interval 등을 함께 고려합니다.

---

## 질문 268. Reproducibility가 AI 연구에서 중요한 이유는 무엇인가요?

**답변:** 다른 연구자가 같은 조건과 절차에서 유사한 결과를 얻을 수 있어야 연구 결과의 신뢰성과 검증 가능성이 높아지기 때문입니다.

---

## 질문 269. Error Analysis란 무엇인가요?

**답변:** 모델이 실패한 사례를 유형별로 분류하고 원인을 분석해 데이터, 모델, Retrieval, Prompt 등 개선 지점을 찾는 과정입니다.

---

## 질문 270. GomsBook AI 연구계획을 설명해보세요.

**답변:** EPUB 구조와 Metadata를 활용한 Structure-aware RAG 및 Agent 기반 접근성 자동화를 설계하고, 일반 Retrieval/Workflow Baseline과 비교해 검색 품질과 작업 성공률을 정량 평가하는 연구로 설명할 수 있습니다.

---

## 질문 271. Overfitting이란 무엇인가요?

**답변:** 학습 데이터에는 매우 잘 맞지만 새로운 데이터에서 성능이 떨어지는 현상으로 모델이 학습 데이터의 노이즈까지 과도하게 학습한 상태입니다.

---

## 질문 272. Underfitting이란 무엇인가요?

**답변:** 모델이 데이터의 핵심 패턴도 충분히 학습하지 못해 학습 데이터와 평가 데이터 모두에서 성능이 낮은 상태입니다.

---

## 질문 273. Bias-Variance Tradeoff란 무엇인가요?

**답변:** 모델 복잡도가 증가하면 Bias는 감소하고 Variance는 증가하는 경향이 있으며 두 오류 사이의 균형으로 일반화 성능을 높이는 개념입니다.

---

## 질문 274. Train, Validation, Test Dataset의 역할은 무엇인가요?

**답변:** Train은 파라미터 학습, Validation은 모델·Hyperparameter 선택, Test는 최종 일반화 성능의 독립 평가에 사용합니다.

---

## 질문 275. Cross Validation이란 무엇인가요?

**답변:** 데이터를 여러 Fold로 나누어 학습과 검증을 반복해 제한된 데이터에서 일반화 성능을 더 안정적으로 추정하는 방법입니다.

---

## 질문 276. Regularization이란 무엇인가요?

**답변:** 모델이 학습 데이터에 과도하게 맞는 것을 억제해 일반화 성능을 높이는 기법의 총칭입니다.

---

## 질문 277. L1과 L2 Regularization의 차이는 무엇인가요?

**답변:** L1은 절댓값 penalty로 희소한 Weight를 유도하고 L2는 제곱 penalty로 큰 Weight를 부드럽게 억제합니다.

---

## 질문 278. Dropout이란 무엇인가요?

**답변:** 학습 중 일부 뉴런 출력을 확률적으로 0으로 만들어 특정 뉴런 조합에 과도하게 의존하는 것을 줄이는 Regularization입니다.

---

## 질문 279. Early Stopping이란 무엇인가요?

**답변:** Validation 성능이 더 이상 개선되지 않거나 악화될 때 학습을 중단해 Overfitting과 불필요한 학습을 줄이는 방법입니다.

---

## 질문 280. AI 실험에서 Data Leakage란 무엇인가요?

**답변:** Train 정보가 Validation/Test 또는 Feature 생성 과정에 유입돼 실제보다 과도하게 좋은 평가 결과가 나오는 문제입니다.

---

## 질문 281. Gradient Descent란 무엇인가요?

**답변:** Loss의 Gradient 반대 방향으로 파라미터를 반복 갱신해 목적함수를 최소화하는 최적화 방법입니다.

---

## 질문 282. SGD와 Mini-batch Gradient Descent의 차이는 무엇인가요?

**답변:** 좁은 의미의 SGD는 한 샘플로 Gradient를 추정하고 Mini-batch는 여러 샘플 묶음으로 계산해 연산 효율과 Gradient 안정성을 절충합니다.

---

## 질문 283. Momentum이란 무엇인가요?

**답변:** 과거 Gradient의 이동 방향을 누적해 진동을 줄이고 일관된 방향의 업데이트를 가속하는 최적화 기법입니다.

---

## 질문 284. Adam Optimizer란 무엇인가요?

**답변:** Gradient의 1차 모멘트와 2차 모멘트 이동평균을 사용해 파라미터별 Learning Rate를 적응적으로 조정하는 Optimizer입니다.

---

## 질문 285. Learning Rate가 중요한 이유는 무엇인가요?

**답변:** 너무 크면 발산하거나 최적점을 지나치고 너무 작으면 학습이 매우 느리거나 나쁜 지점에 오래 머물 수 있기 때문입니다.

---

## 질문 286. Vanishing Gradient란 무엇인가요?

**답변:** 역전파 과정에서 Gradient가 반복적으로 작아져 앞쪽 Layer의 파라미터가 거의 업데이트되지 않는 현상입니다.

---

## 질문 287. Exploding Gradient란 무엇인가요?

**답변:** 역전파 과정에서 Gradient가 지나치게 커져 파라미터 업데이트가 불안정해지거나 수치적으로 발산하는 현상입니다.

---

## 질문 288. Xavier Initialization이란 무엇인가요?

**답변:** 입출력 분산을 고려해 Weight 초기 분산을 설정하여 신호와 Gradient의 분산을 안정적으로 유지하려는 초기화 방법으로 tanh 계열에 흔히 사용됩니다.

---

## 질문 289. He Initialization이란 무엇인가요?

**답변:** ReLU 계열 활성화의 특성을 고려해 Weight 분산을 설정하는 초기화 방법입니다.

---

## 질문 290. Batch Normalization과 Layer Normalization의 차이는 무엇인가요?

**답변:** BatchNorm은 주로 Batch 통계를 이용해 정규화하고 LayerNorm은 한 샘플의 Feature 차원을 기준으로 정규화합니다. Transformer에서는 LayerNorm이 일반적입니다.

---

## 질문 291. Loss Function이란 무엇인가요?

**답변:** 모델의 예측과 목표 사이의 오차를 수치화한 목적 함수이며 학습은 보통 이 값을 최소화하도록 파라미터를 조정합니다.

---

## 질문 292. MSE(Mean Squared Error)란 무엇인가요?

**답변:** 예측값과 실제값 차이의 제곱을 평균한 회귀 Loss로 큰 오차에 더 큰 penalty를 줍니다.

---

## 질문 293. Cross Entropy란 무엇인가요?

**답변:** 정답 확률분포와 모델 예측 확률분포의 차이를 측정하는 대표적인 분류 Loss입니다.

---

## 질문 294. Binary Classification과 Multi-class Classification의 차이는 무엇인가요?

**답변:** Binary Classification은 두 클래스 중 하나를, Multi-class Classification은 세 개 이상의 상호배타적 클래스 중 하나를 예측합니다.

---

## 질문 295. Softmax란 무엇인가요?

**답변:** 여러 Logit을 지수화·정규화해 합이 1인 확률분포로 변환하는 함수입니다.

---

## 질문 296. Log-Likelihood란 무엇인가요?

**답변:** 관측 데이터가 주어진 모델 파라미터에서 발생할 가능성인 Likelihood에 로그를 취한 값이며 곱을 합으로 바꿔 계산과 최적화를 쉽게 합니다.

---

## 질문 297. Maximum Likelihood Estimation(MLE)이란 무엇인가요?

**답변:** 관측 데이터의 Likelihood를 가장 크게 만드는 파라미터를 선택하는 추정 방법입니다.

---

## 질문 298. Entropy란 무엇인가요?

**답변:** 확률분포의 평균적인 불확실성 또는 정보량을 나타내며 H(P)=-Σp(x)log p(x)로 표현합니다.

---

## 질문 299. KL Divergence란 무엇인가요?

**답변:** 한 확률분포 P를 다른 분포 Q로 근사할 때 발생하는 정보 손실을 측정하며 KL(P||Q)=ΣP(x)log(P(x)/Q(x))입니다.

---

## 질문 300. Perplexity란 무엇인가요?

**답변:** 언어모델이 다음 Token을 얼마나 불확실하게 예측하는지를 나타내는 지표로 평균 Cross Entropy L에 대해 PPL=exp(L)로 표현할 수 있으며 낮을수록 예측 확률이 높습니다.

---
