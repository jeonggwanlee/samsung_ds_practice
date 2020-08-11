# 삼성 대화시스템 실습과제

0. 환경세팅

(a) ConvLab과 함께 repository를 clone해옵니다.
```
git clone --recurse-submodules https://github.com/tzs930/samsung_dialogue_tutorial.git
```
(b) Anaconda Environment를 생성합니다.
```
conda env create -f environment.yaml
```
(c) Anaconda Environment를 활성화합니다.
```
conda activate 0813_dialogue_system 
```
(d) ConvLab-2 패키지를 설치합니다.
```
pip install -e ./ConvLab-2
```

-----------

`practice_problem.ipynb` 파일을 완성하는 것이 이 과제의 목표입니다. 

**\[실습문제]** Success Rate를 기준으로 상위 3가지 모델을 찾고, 아래 표를 완성하세요.

**\[힌트]** 여러 개의 system agent를 만들고 아래의 코드를 활용해 한번에 돌리실 수 있습니다.

**\[주의]**  실습과제 제출시 실행기록을 반드시 남겨서 제출해야 합니다.

Rank      | NLU       | DST       | Policy    | NLG          | Success rate | Book rate | Inform P | Inform R | Inform F1 | Turn(succ/all) |
--------- | --------- | --------- | --------- | :----------: | :----------: | --------- | -------- | --------- | -------- | -------------- |
1         | -         | -         | -         | -            | -            | -         | -        | -         | -        | -              |
2         | -         | -         | -         | -            | -            | -         | -        | -         | -        | -              |
3         | -         | -         | -         | -            | -            | -         | -        | -         | -        | -              |
