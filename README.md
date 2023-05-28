### Hi there 👋

<!--
**sgr1118/sgr1118** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## 나의 대표적인 프로젝트

|No|프로젝트명|Repo|
|-|-|-|
|1|맥주 리뷰 데이터 감정 분석 인공지능|[📂](https://github.com/sgr1118/Beer_Sentiment_analysis)|
|2|대화 데이터 상황 요약 인공지능|[📂](https://github.com/AIFFEL-NLP-PROJECT/Aiffelthon)|

## 프로젝트 별 간단 설명

### 1. 맥주 리뷰 데이터 감정 분석 인공지능
---
### 간단 설명
- 감정 분석을 통하여 고객(유저)이 느끼는 감정을 분류한 결과를 바탕으로 제품 기획 및 마케팅 활용에 근거로 사용할 수 있다.
---
### 사용 모델
- T5
---
### 성능 개선을 위한 방법
- 데이터 증강 사용
---
### 최종 기록 : Binary Class 분류 결과 
|Model|Accuracy|F1-Score(macro)|Precision(macro)|Recall(macro)|
|---|---|---|---|---|
|T5(GPT API and MultinomialNB) - SR(동의어 교체)|0.946|0.946|0.946|0.946|
---
### 추가적인 개선 사항
### 1. 맥주의 종류에 따른 감정 분석 기준 세부화
- 예를 들어 라거라는 맥주 종류 중 헬레스라는 것이 있다. 헬레스는 기본적으로 매우 목넘김이 너무 편해 'watery'하다고 할 수 있다. 
다만 이런 표현이 특징이 뚜렷한 맥주에 대한 리뷰에서는 부정적으로 받아들여질 가능성이 있다. 그러므로 맥주에 특성을 반영하여 감정을 분류할 필요가 있다.

### 2. 중립적인 리뷰 구분
- 맥주 리뷰에서 단순히 상품을 설명하는 내용이거나 감정이 크게 나타나지않아 중립 라벨링 처리가 필요할 것으로 생각한다.
