# 우아한 테크러닝, 노션 만들기

## 구성

- yarn workspace + mono repo
- frontend: create-react-app + typescript
- backend: nestjs + typescript

## 목표

1. 데스크탑 기준의 노션같은 서비스

2. 실시간 수정 지원

3. 리치 마크다운 지원

4. 출판 알림 혹은 rss 피드 지원

## 도구

### 마크다운

#### 통합 에디터 형태

1. [rich-markdown-editor](https://github.com/outline/rich-markdown-editor)

    - star 2K
    - React and Prosemirror, styled-components 기반
    - [Outline](https://www.getoutline.com/) 프로젝트 지원용으로 제작됨.

2. [canner-slate-editor](https://github.com/Canner/canner-slate-editor)

    - star 1.1K
    - [Slate framework](https://docs.slatejs.org/) 기반임.
    - 범용

#### 커스텀 에디터 형태

1. [ProseMirror](https://github.com/prosemirror)

    - [문서](https://prosemirror.net/)가 투박해보임
    - repo가 조각조각

2. [Slate framework](https://github.com/ianstormtaylor/slate) *유력*

    - *star 20.8K*
    - [문서](https://docs.slatejs.org/)가 이뻐보임
