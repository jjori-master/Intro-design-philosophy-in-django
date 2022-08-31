# intro-design-philosophy-in-django



### 개요

* 이진석 님의 [장고 설계철학으로 시작하는 파이썬 장고 입문](https://www.inflearn.com/course/%EC%9E%A5%EA%B3%A0-%EC%84%A4%EA%B3%84%EC%B2%A0%ED%95%99-%EC%9E%85%EB%AC%B8) 강의 실습 저장소 입니다.
* 개발 환경 설정은 [강의 자료 PDF](https://www.inflearn.com/course/%EC%9E%A5%EA%B3%A0-%EC%84%A4%EA%B3%84%EC%B2%A0%ED%95%99-%EC%9E%85%EB%AC%B8/unit/120979) 에 자세히 기술 되어 있으나 간단히 해당 문서에 기술합니다.



#### 윈도우 개발 환경 설정

##### 1. Scoop 설치 및 패키지 설치

* [[환경설정] (필수) Scoop 설치.md](https://github.com/jjori-master/pre-blog/blob/master/dev-env/%5B%ED%99%98%EA%B2%BD%EC%84%A4%EC%A0%95%5D%20(%ED%95%84%EC%88%98)%20Scoop%20%EC%84%A4%EC%B9%98.md) 를 참조하여 Scoop 설치

```bash
# install packages
scoop install pyenv
scoop install nerd-fonts/FiraCode-NF-Mono
scoop install nerd-fonts/CascadiaCode-NF-Mono
```

##### 2. pyenv

* [[환경설정] pyenv (윈도우).md](https://github.com/jjori-master/pre-blog/blob/master/dev-env/%5B%ED%99%98%EA%B2%BD%EC%84%A4%EC%A0%95%5D%20pyenv%20(%EC%9C%88%EB%8F%84%EC%9A%B0).md) 를 참조하여 `pyenv` 를 설정합니다.



#### 프로젝트 설정

##### 1. 가상 환경 생성

```bash
python -m venv venv
venv\scripts\activate # 윈도우 venv 폴더의 가상환경 활성화
```

##### 2. 파이썬 패키지 설치

```bash
pip install -r requirements.txt
```

