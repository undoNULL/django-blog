# django-blog

## 목적

api 연습용 블로그 

별 기능이 없다. 대신 테그로 검색 가능하다는 점이 아이덴티티이다 

## **주요 기능**

- **글 작성 (Post):** 제목, 내용, 카테고리, 태그, 작성일, 수정일, 썸네일 이미지 등을 포함합니다.
- **글 조회 (Post):**
    - 전체 글 목록 조회 (페이징, 최신 글 순, 카테고리/태그별 필터링, 검색 기능 포함)
    - 특정 글 상세 조회 (ID 기반)
- **글 수정 (Post):** 작성자가 자신의 글을 수정합니다.
- **글 삭제 (Post):** 작성자 또는 관리자가 글을 삭제합니다.
- **사용자 관리 (User):**
    - 회원 가입, 로그인, 로그아웃
    - 사용자 정보 조회, 수정 (프로필 이미지 포함)
- **댓글 기능 (Comment):**
    - 글에 댓글 작성, 조회, 수정, 삭제
    - 댓글 목록 조회 (글 기반)
- **카테고리 관리 (Category):**
    - 카테고리 생성, 조회, 수정, 삭제
    - 글 작성 시 카테고리 선택
- **태그 기능 (Tag):**
    - 태그 생성, 조회, 수정, 삭제
    - 글 작성 시 태그 선택
- **검색 기능 (Search):** 제목, 내용, 작성자 기반 검색
- **권한 관리:**
    - 일반 사용자, 작성자, 관리자 역할 분리
    - 각 역할에 따른 기능 접근 권한 설정 (예: 관리자만 카테고리/태그 관리 가능)


## **api문서**
- https://pineapple-gallium-fe3.notion.site/API-19b6d6d9213d80508269c14f02620794

## **실행 방법**
- 