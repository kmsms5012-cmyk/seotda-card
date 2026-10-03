# 섯다 카드 URL 사이트 템플릿

이 폴더는 카카오톡 링크 미리보기를 위한 정적 웹사이트 템플릿입니다.

## 배포 방법
1. GitHub에 새 저장소를 만듭니다. (예: `seotda-card`)
2. 이 폴더 내용 전체를 업로드합니다.
3. GitHub Pages를 켭니다.
4. 배포 주소가 정해지면 `YOUR_BASE_URL.txt`에 적힌 예시처럼 실제 주소를 확인합니다.
5. `card` 폴더 아래의 모든 `index.html` 파일에서 `__BASE_URL__`를 실제 배포 주소로 한 번에 바꿉니다.
   예: `https://YOUR-ID.github.io/seotda-card`
6. 다시 업로드하면 끝입니다.

## 봇 코드에 넣을 값
```js
var CARD_BASE = "https://YOUR-ID.github.io/seotda-card/card/";
```

그러면 카드 URL은 예를 들어 아래처럼 됩니다.
- 1광: `https://YOUR-ID.github.io/seotda-card/card/01A/`
- 8광: `https://YOUR-ID.github.io/seotda-card/card/08A/`
- 10월 열끗: `https://YOUR-ID.github.io/seotda-card/card/10A/`

## 주의
- `04A` 이미지는 우측 하단에 퍼즐 박스가 함께 보입니다.
- `05B` 이미지는 해상도가 작고 약간 잘려 있습니다.
원하시면 나중에 이 두 장은 더 깔끔한 이미지로 교체하는 것을 추천합니다.
