# Contributing Guidelines

이 프로젝트에 기여하기 위에 다음 지침을 꼭 읽어주세요.

## 실행방법

```python
# 프로젝트 종속 패키지 설치
pip install -r requirements.txt

# notebooks폴더 하위의 모든 .ipynb를 .py로 변환
jupytext --to py notebooks/*ipynb

# notebooks폴더 하위의 모든 py를 .ipynb로 변환
jupytext --to ipynb notebooks/*.py

# 파이썬 코드포멧팅
black .
```