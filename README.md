# 우아한테크코스 미션 저장소

원본 최종 미션 커밋 이력을 그대로 이식 후, 별도의 폴더로 정리하는 방식으로 기록

## 프리코스
|   | 미션명 | 기간 | 저장소 |
|---|---|---|---|
| 1 | 온보딩 | '22.10.26 ~ '22.11.01 | [GitHub Repository](https://github.com/gabrielyoon7/javascript-onboarding/tree/gabrielyoon7) |
| 2 | 숫자 야구 | '22.11.02 ~ '22.11.08 | [GitHub Repository](https://github.com/gabrielyoon7/javascript-baseball/tree/gabrielyoon7) |
| 3 | 로또 | '22.11.09 ~ '22.11.15 | [GitHub Repository](https://github.com/gabrielyoon7/javascript-lotto-precourse/tree/gabrielyoon7) |
| 4 | 다리 건너기 | '22.11.16 ~ '22.11.22 | [GitHub Repository](https://github.com/gabrielyoon7/javascript-bridge/tree/gabrielyoon7) |

- [[회고] 우아한테크코스 5기 프리코스 (FE)](https://leirbag.tistory.com/125)
- [우아한테크코스 5기 프리코스 (FE) 1차 합격!](https://leirbag.tistory.com/126)

## 프리코스(최종)
|   | 미션명 | 기간 | 저장소 |
|---|---|---|---|
| 1 | 점심 메뉴 추천 | '22.12.17 | [GitHub Repository](https://github.com/gabrielyoon7/javascript-menu/tree/gabrielyoon7) |

- [우아한테크코스 5기 (FE) 최종 코딩테스트 후기](https://leirbag.tistory.com/127)

---

## 레벨 1
|   | 미션명 | 기간 | 페어 | Step1 | Step2 |
|---|---|---|---|---|---|
| 1 | 자동차 경주 게임 | '23.02.07 ~ '23.02.13 | [윤생(이윤성)](https://github.com/2yunseong) | [Pull Request](https://github.com/woowacourse/javascript-racingcar/pull/153) | [Pull Request](https://github.com/woowacourse/javascript-racingcar/pull/208)  |
| 2 | 로또 | '23.02.14 ~ '23.02.27 | [도담(김민재)](https://github.com/D0Dam) | [Pull Request](https://github.com/woowacourse/javascript-lotto/pull/176) | [Pull Request](https://github.com/woowacourse/javascript-lotto/pull/252)  |
| 3 | 점심뭐먹지 | '23.02.28 ~ '23.03.13 | [라잇(강영민)](https://github.com/kangyeongmin) | [Pull Request](https://github.com/woowacourse/javascript-lunch/pull/19) | [Pull Request](https://github.com/woowacourse/javascript-lunch/pull/58)  |
| 4 | 영화리뷰 | '23.03.14 ~ '23.03.27 | [야미(이다인)](https://github.com/feb-dain) | [Pull Request](https://github.com/woowacourse/javascript-movie-review/pull/14) | [Pull Request](https://github.com/woowacourse/javascript-movie-review/pull/81)  |

- [우아한테크코스 한 달 생활기](https://leirbag.tistory.com/134)
- [우아한테크코스 5기 FE 레벨 1을 마치며...](https://leirbag.tistory.com/141)

## 레벨 2
|   | 미션명 | 기간 | 페어 | PR(Step1) | PR(Step2) | PR(Step3) |
|---|---|---|---|---|---|---|
| 1 | 다시,점심뭐먹지 | '23.04.11 ~ '23.04.17 | [제레미(김민석)](https://github.com/shackstack) | [Pull Request](https://github.com/woowacourse/react-lunch/pull/1) | [Pull Request](https://github.com/woowacourse/react-lunch/pull/59) |  |
| 2 | 페이먼츠 | '23.04.18 ~ '23.05.08 | [노아(김홍동)](https://github.com/nlom0218) | [Pull Request](https://github.com/woowacourse/react-payments/pull/187) | [Pull Request](https://github.com/woowacourse/react-payments/pull/254) | [Pull Request](https://github.com/woowacourse/react-payments/pull/291) |  |
| 3 | 장바구니 | '23.05.09 ~ '23.05.22 | [우코(김유권)](https://github.com/ukkodeveloper) | [Pull Request](https://github.com/woowacourse/react-shopping-cart/pull/161) | [Pull Request](https://github.com/woowacourse/react-shopping-cart/pull/231) |
| 4 | 장바구니(협업) | '23.05.23 ~ '23.06.05 | [파인(임낭경)](https://github.com/nangkyeonglim) | [Pull Request](https://github.com/woowacourse/react-shopping-cart-prod/pull/78) | [Pull Request](https://github.com/woowacourse/react-shopping-cart-prod/pull/148) | 

## 레벨 3

팀 프로젝트

### [카페인 홈페이지 바로가기](https://carffe.in)


- [카페인 Repository](https://github.com/woowacourse-teams/2023-car-ffeine)
- [카페인 팀 블로그](https://car-ffeine.github.io/archive)

## 레벨 4
|   | 미션명 | 기간  | PR(Step1) | PR(Step2) |
|---|---|---|---|---|
| 1 | 프론트엔드 성능 베이스캠프 | '23.08.31 ~ '23.09.12 |  |  |
| 2 | 재사용 가능한 레이아웃 컴포넌트 설계와 구현 | '23.09.13 ~ '23.10.03 |  |  |
| 3 | 프론트엔드의 렌더링 | '23.10.04 ~ '23.10.23 |  |  |


---

## 미러링 방식

이름이 겹칠만한 파일이나 폴더를 생성하지 않고, 프로젝트 수신 이후에 옮겨 줄 백업용 폴더만을 생성한다.

```
git remote add <REPO_NAME> https://github.com/<USER_NAME>/<REPO_NAME>.git
```

```
git fetch <REPO_NAME> <BRANCH_NAME>
```

```
git merge <REPO_NAME>/<BRANCH_NAME> --allow-unrelated-histories
```

파일 수신 이후 폴더 및 파일들 원하는 위치(백업용 폴더)에 옮겨주기 (정리)

전체 커밋 및 푸쉬
