# 프로젝트 소개

원티드 프리온보딩 2주차

광고 대시보드 서비스 팀프로젝트 입니다.

# 🚀 [배포 링크(예정)](/)

# 팀원

| 이름   |       팀 구성       |                                                                                기능 구현 및 역할                                                                                 |
| ------ | :-----------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 김수빈 | 팀원 </br> Frontend |                                                              - mui 라이브러리로 ui 구현 </br> - table data api 작업                                                              |
| 김민주 | 팀원 </br> Frontend | - 모달 및 카드 즐겨찾기 버튼 활성화 </br> - CSS 수정 </br> - 로고 클릭시 홈으로 이동 및 전체 데이터 출력 </br> - Refactoring: 주석, 죽은 코드 제거 및 함수,변수 naming 최종 정리 |
| 이상지 | 팀장 </br> Frontend |             - 기획, UI/UX 디자인 및 레이아웃 </br> - 프로젝트 초기세팅 </br> - 헤더 구현 </br> - 드롭다운 연관 검색어 기능 구현 </br> - 스크럼 진행 및 개발일정 관리             |
| 이혜림 | 팀원 </br> Frontend |                                  - ReChart.js 로 차트들 제작 </br> - Recoil로 날짜 데이터를 전역으로 관리 / 동기화 </br> - 차트 테마를 바뀌게 하는 기능! </br>                               |
| 홍승연 | 팀원 </br> Frontend |                                               - 수빈님과 함께 table data api 작업 </br> -  table chart 렌더링

</br>
</br>

# 기술 스택

`React.js`
`TypeScript`

`recoil`
`axois`
`date-fns`
`MUI`
`json-server`
`classnames`
`styled-components`

</br>
</br>

# 구현 조건

1. 라우터를 활용하여 `sub routing`을 구현한다.
2. `chart` 라이브러리를 이용하여 라인 차트, 스택차트를 구현한다.
3. `table`을 구현한다.

</br>

# 폴더 구조

```text
폴더 구조 정리
```

추가예정

</br>

# 상세 기능 구현 설명

### 수빈

**UI 구현**

- MUI 라이브러리를 사용하여 UI 구현
- 반응형

<img width="1437" alt="main" src="https://user-images.githubusercontent.com/90506668/179884153-dc3610e4-b6bb-4b9f-bdf4-287d3165d590.png">
<br>
<br>
<img width="250" alt="mobile_main" src="https://user-images.githubusercontent.com/90506668/179884285-538479e7-19bc-43da-a13a-750568af9e7b.png">

<br>
<br>

**table data api**
<img width="392" alt="platform_sum" src="https://user-images.githubusercontent.com/90506668/179885603-c1f5d1b5-711b-4950-bc64-ee41c4e9b249.png">
각 회사 별 데이터들을 합산하여 {name: 'keyname', sum: 값} 구조로 리턴

</br>

### 혜림

- ReChart.js 로 차트들 제작
  - 동적으로 바뀌는 차트 제작!
- Recoil로 날짜 데이터를 전역으로 관리 / 동기화 
  - 주말 기준으로 일주일씩 끊고 start날짜가 주말이 아닐 경우에는 앞을 끊어서 보여줍니다.
- 차트 테마를 바뀌게 하는 기능! 
  - 드롭다운을 누르면 차트의 테마를 바꿀수 있음!

</br>

### 승연

- 수빈님과 함께 table data api 작업

![1](https://user-images.githubusercontent.com/69149030/179942515-b3498c25-004f-4744-9b30-e952f455bc82.png)

- table chart 렌더링

![1](https://user-images.githubusercontent.com/69149030/179942780-c89c99a2-f395-4ac8-add8-b08f78496abc.png)
