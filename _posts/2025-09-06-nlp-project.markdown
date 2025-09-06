---
layout: post
title: [논문리뷰] Brain Foundation Models
date: 2025-09-06 19:20:23 +0900
category: AI
---
# [논문리뷰] Brain Foundation Models
> Hello!

이 논문은 Brain Foundation Model에 대한 Survey를 다룬다.
Foundation Model이란 라벨이 없는 데이터에 대해 사전학습된 모델을 의미한다.
Brain Data로 학습된 데이터로, 관련된 다양한 하위 작업을 수행하는 모델의 개발이 궁극적인 목표이다.

현재 활용되고 있는 데이터는 fMRI, ERR 등이 있다.
부족한 데이터를 나타내기 위한 모달리티 간의 통합이 필요하지 않을까? 라는 생각에서 motivation을 얻었다.

이미지와 텍스트를 fusion하는 방법론으로 contrastive representaion learning을 가장 먼저 떠올릴 수 있다.

reference: https://www.themoonlight.io/en/review/brain-foundation-models-a-survey-on-advancements-in-neural-signal-processing-and-brain-discovery

https://daebaq27.tistory.com/97

이외에도 정확한 지식을 모델에 주입하기 위한 방법론으로 Knowledge Graph를 활용하는 방법론에 대한 탐구도 진행해보면 좋겠다.
https://www.themoonlight.io/ko/review/biomedical-knowledge-graph-a-survey-of-domains-tasks-and-real-world-applications