# 핸즈온 머신러닝 with 사이킷런, 파이토치

이 책은 파이썬으로 머신 러닝의 기초를 배우는 것이 목표입니다. 이 깃허브 저장소에는 <핸즈온 머신러닝 with 사이킷런, 파이토치>(한빛미디어, 2026)의 예제 코드와 연습 문제에 대한 솔루션이 포함되어 있습니다: ([교보문고](https://product.kyobobook.co.kr/detail/S000221505880), [Yes24](https://www.yes24.com/product/goods/197068692), [알라딘](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=403219344&start=pcsearch_auto), [한빛미디어](https://www.hanbit.co.kr/books/핸즈온-머신러닝-with-사이킷런-파이토치?code=B6522995423))

<a href="https://tensorflow.blog/handson-mlp/"><img src="https://i0.wp.com/tensorflow.blog/wp-content/uploads/2026/10/%EC%9E%85%EC%B2%B4%ED%91%9C%EC%A7%80.png?resize=1743%2C2048&ssl=1" title="book" width="500" border="0" /></a>

**노트**: 이 책의 텐서플로/케라스 버전을 찾고 있다면 [rickiepark/handson-ml3](https://github.com/rickiepark/handson-ml3)를 확인하세요.

## 빠르게 시작하기

### 아무것도 설치하지 않고도 온라인에서 이 노트북을 실행하고 싶은가요?

- <a href="https://colab.research.google.com/github/rickiepark/handson-mlp/blob/main/" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> (추천)

⚠ _코랩은 임시 환경을 제공하므로 일정 시간이 지나면 모든 작업이 삭제되므로 중요한 데이터는 반드시 다운로드하세요._

### 코드를 실행하지 않고 노트북을 빠르게 살펴보고 싶은가요?

- <a href="https://nbviewer.jupyter.org/github/rickiepark/handson-mlp/blob/main/index.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a>

- [깃허브의 노트북 뷰어](https://github.com/rickiepark/handson-mlp/blob/main/index.ipynb)로도 볼 수 있지만 이상적이지는 않습니다. 페이지가 느리게 열리고 수학 방정식이 이따금 잘못 표시되거나 용량이 큰 노트북은 열리지 않는 경우가 많습니다.

### 이 프로젝트를 로컬 컴퓨터에 설치하고 싶은가요?

[INSTALL.md](INSTALL.md) 문서를 참고하세요.


# FAQ

**어떤 파이썬 버전을 사용해야 하나요?**

Python 3.12을 권장합니다. 위의 설치 가이드를 따르면 이 버전이 설치됩니다. 3.10과 3.11도 작동하지만 일부 라이브러리는 아직 3.13 버전을 지원하지 않습니다.

**`load_housing_data()`를 호출하면 에러가 발생합니다**

HTTP 오류가 발생하면 노트북에서와 똑같은 코드를 실행하고 있는지 확인하세요(복사/붙여넣기로 다시 실행해 보세요). 문제가 지속되면 네트워크 구성을 확인하세요. SSL 오류인 경우, 다음 질문을 참조하세요.

**MacOSX에서 SSL 오류가 발생합니다**.

SSL 인증서를 설치해야 합니다([스택오버플로 질문](https://stackoverflow.com/questions/27835619/urllib-and-ssl-certificate-verify-failed-error) 참조하세요). 공식 웹사이트에서 파이썬을 다운로드한 경우, 터미널에서 `/Applications/Python\ 3.12/Install\ Certificates.command`를 실행합니다(`3.12`를 설치한 버전으로 변경). MacPorts를 사용하여 파이썬을 설치한 경우, 터미널에서 `sudo port install curl-ca-bundle`을 실행합니다.

**이 프로젝트를 로컬에 설치했습니다. 최신 버전으로 업데이트하려면 어떻게 해야 하나요?**

[INSTALL.md](INSTALL.md)를 참고하세요.

**아나콘다를 사용할 때 파이썬 라이브러리를 최신 버전으로 업데이트하려면 어떻게 해야 하나요?**

[INSTALL.md](INSTALL.md)를 참고하세요.

## 도움을 주신 분들

유용한 피드백을 제공하거나 이슈를 제기하거나 풀 리퀘스트를 보내는 등 이 [프로젝트에 기여](https://github.com/rickiepark/handson-mlp/graphs/contributors)해 주신 모든 분들께 감사의 말씀을 드립니다.
