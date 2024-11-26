# Developing a Machine Learning-Based Algorithm for Assessing Enterprise Promisingness_sub study 2
project

## Purpose
기존의 유망 아이템 탐색은 규칙 기반의 알고리즘으로 작동하여 유연성과 정확성에서 한계를 나타냄, 이에 본 과제에서는 최근 많은 발전이 이루어진 거대 언어 모델(Large Language Model, LLM)을 활용하여 아이템/비아이템 분류 모델을 고도화

## Methodology
Instruction Induction을 수행하여 획득한 지시문과, 사용자와 LLM이 공용으로 사용하는 아이템 문서에 대한 정의를 활용하여 프롬프트 앤지니어링 수행

  - Model : Llama3(70B)
  - Dataset : KISTI 선정 Wiki 문서 데이터 셋, KIPRIS 특허 문서

## Result
기존 아이템 분류 프롬프트 방식보다 최대 26.79%p 성능 향상 확인