# NLP

## BERT (Huggingface) : 영화리뷰 감성(긍정/부정) 분석하기
- Pretrained model : Bert
- TensorFlow와 Keras를 사용하여 BERT 기반의 모델을 컴파일하고 훈련
- FineTuning (사전학습모델의 파라미터를 추가적으로 학습, 일부 파라미터만 수정하거나 전체 파라미터를 모두 수정)
- Huggin Face에서 제공하는 분류를 위한 BertForSequenceClassification 클래스 사용 : 기본적인 BERT 모델에 신경망 층이 추가된 구조를 바로 사용할 수 있다. 미세 조정 방식은 데이터를 새로 학습해야 하기 때문에 정답 라벨이 있는 데이터를 
- 학습/평가 데이터로 구분해야 한다. 새로 학습을 진행할 때 초기 파라미터는 사전학습 모델의 파라미터가 그대로 사용된다.
