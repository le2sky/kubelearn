# k8s-learn

k8s study repository refer ->[kubernetes docs](https://kubernetes.io/ko/docs/concepts/overview/what-is-kubernetes/)

## 누군가 k8s가 무엇이냐고 묻는다면?

```
쿠버네티스는 컴퓨터 클러스터에 애플리케이션 컨테이너의 배치(스케줄링) 및 실행을 오케스트레이션하는 운영 수준의 오픈소스 플랫폼이다.
```

## 누군가 컨트롤 플레인이 무엇이냐고 묻는다면?

```
컨트롤 플레인은 실행 중인 애플리케이션을 호스팅하기 위해 사용되는 노드와 클러스터를 관리한다.
```

## 누군가 디플로이먼트가 뭐냐고 묻는다면?

```
디플로이먼트는 애플리케이션 인스턴스를 생성하고 업데이트하는 역할을 담당한다
애플리케이션이 쿠버네티스 상에 배포되려면 지원되는 컨테이너 형식 중 하나로 패키지 되어야한다. 즉, 도커를 쓰라는 말이다.
```

## 누군가 파드가 뭐냐고 묻는다면?

```
파드(Pod) 는 쿠버네티스에서 생성하고 관리할 수 있는 배포 가능한 가장 작은 컴퓨팅 단위이다.
하나 이상의 컨테이너의 그룹이며 클러스터에서 실행중인 워크로드의 일부를 나타낸다.
공유 스토리지 (볼륨), IP 주소 그리고 그것을 동작시키는 방식에 대한 정보를 포함하고 있다.
```

## bookmark

### 기본 개념

- [쿠버네티스란 무엇인가](https://github.com/le2sky/kubelearn/blob/documentation/concept/%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4%EB%9E%80%20%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80/%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4%EB%9E%80.md)

- [쿠버네티스 컴포넌트](https://github.com/le2sky/kubelearn/blob/documentation/concept/%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8/%EC%BF%A0%EB%B2%84%EB%84%A4%ED%8B%B0%EC%8A%A4%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8.md)

### k8s 모듈

- [모듈 1. 클러스터 생성](https://github.com/le2sky/kubelearn/blob/documentation/k8s-module/%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0/%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0%20%EC%83%9D%EC%84%B1.md)
- [모듈 2. 디플로이먼트 생성](https://github.com/le2sky/kubelearn/blob/documentation/k8s-module/%EB%94%94%ED%94%8C%EB%A1%9C%EC%9D%B4%EB%A8%BC%ED%8A%B8/%EB%94%94%ED%94%8C%EB%A1%9C%EC%9D%B4%EB%A8%BC%ED%8A%B8%20%EC%83%9D%EC%84%B1.md)
- [모듈 3. 파드와 노드](https://github.com/le2sky/kubelearn/blob/documentation/k8s-module/%ED%8C%8C%EB%93%9C%EC%99%80%20%EB%85%B8%EB%93%9C/%ED%8C%8C%EB%93%9C%EC%99%80%20%EB%85%B8%EB%93%9C.md)
