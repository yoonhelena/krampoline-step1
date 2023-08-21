# krampoline-step1

## 소개

`krampoline-step1`은 krampoline의 가장 기본적인 예제입니다. 
이 저장소에서는 `index.py`를 사용하여 3000번 포트에서 서버를 열고 "hello krampoline!"를 출력하는 예제를 제공합니다.

쿠버네티스 구성은 다음과 같습니다.
![image](https://github.com/MonoKim01/krampoline-step1/assets/85483855/248fb708-aa34-446b-9d0c-8bb30c9bc5f4)



## 필요 사항

- 기본적인 IDE 사용법 (자세한 내용은 가이드 문서 참조)

## 주의 사항

- 꼭 `Dockerfile`과 `k8s` 폴더를 프로젝트에 포함시켜주세요.
  - 프로젝트의 루트 (`/`) 위치에 포함되게 해주세요.
- k8s/deployment.yaml과 k8s/ingress.yaml 파일은 필히 확인하시기 바랍니다.
- `main`브런치에 작성해주세요.
