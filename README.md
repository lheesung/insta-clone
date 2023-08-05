# 웅이야 프론트엔드 과제 - [인스타그램](https://www.instagram.com/) 클론코딩
📆 기한: 08월 16일 23시 59분 까지
🏆 주제: 인스타그램 메인 페이지 클론코딩
### 깃허브
- 위 레포지토리를 **포크하여 포크된 레포지토리를 클론하여 개발**합니다.
- 커밋은 기한동안 주기적으로 이루어져야 합니다.
- 08.14~ 08.16 사이에 **자신의 깃허브 아이디와 같은 이름의 브랜치**를 생성하여 위 레포지토리에 Pull Request(PR)를 생성합니다. 이 때 PR의 제목은 **"[클론코딩]차정원 과제 제출합니다"** 와 같은 형식으로 PR을 생성합니다. PR의 내용에는 자신의 느낀점이나 질문을 작성합니다.

### 커밋 룰
| type | description |
| :---: | :---: |
| ADD | 새로운 기능, 컴포넌트 등 새로운 것이 추가되었을 때 |
| FIX | 기존의 코드에서 잘못된 부분을 수정할 때 |
| REFACTOR | 기존의 있는 코드를 리팩토링 하였을 때 |
| DELETE | 기존의 있던 내용을 삭제하였을 때 |
#### 예시
```bash
git commit -m 'ADD: 사이드 바 컴포넌트 추가'
git commit -m 'FIX: 스토리 섹션 스크롤 방향 수정'
git commit -m 'REFACTOR: 코드 가독성을 높이기 위한 리팩토링'
git commit -m 'DELETE: 사용하지 않는 태그 삭제'
```

### 사용 기술
- package manager는 [yarn](https://yarnpkg.com/)을 사용합니다.
  + [yarn 윈도우 세팅](https://velog.io/@nxnaxx/React-%EA%B0%9C%EB%B0%9C-%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95-yarn%EA%B3%BC-CRA-%EC%84%A4%EC%B9%98)
  + [yarn 맥 세팅](https://velog.io/@seoyaon/React-%EB%A6%AC%EC%95%A1%ED%8A%B8-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0)
- 스타일링은 [styled-components](https://styled-components.com/)를 사용합니다.[(사용방법)](https://github.com/WoongCourse/clone/blob/main/src/docs/styled_components.md)

### 파일구조 및 파일 네이밍 규칙
```bash
├── public
├── src
│   ├── docs
│   ├── components
│   └── pages
└──
``` 
<span style='color: #aaa'>*docs 내의 내용은 수정하지 않습니다.</span>