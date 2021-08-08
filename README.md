# 한시간만에 끝내는 Vue.js 입문
```
210808 유투브 개발자의 품격
```
---

## Vue.js 는 웹프론트엔드 프레임 워크 
```
컴포넌트 기반의 SPA(싱글 페이지 어플리케이션)를 구축할수 있게 해주는 프레임 워크
```

## 컴포넌트
```
- 웹을 구성하는 로고, 메뉴바, 버튼, 모달창 등 웹 페이지 내의 다양한  UI 요소
- 재사용 가능하도록 구조화 한 것
```

## SPA (싱글 페이지 어플리케이션)
```
- 단일 페이지 어플리케이션
- 하나의 페이지 안에서 필요한 영역 부분만 로딩 되는 형태
- 빠른 페이지 변환
- 적은 트래픽 양
```

### Vue CLI 설치
```
npm install -g @vue/cli
npm install vue-cli -global
```
- cli : 뷰의 필요한 폴더 구조나 라이브러리를 자동 설치 해준다
```
vue create test
```
- test 라는 이름의 폴더 생성

```
cd test
npm run serve 
```
- server 아님 serve

```
npm install vue-router --save

라우터 -> 웹 페이지 를 이동하는 방법
	그 부분만 화면을 갱신
npm install vue bootstrap bootstrap-vue
```
- 부트스트랩 뷰 설치
```
main.js 에 아래 코드 넣어주면 부트스트랩 사용 가능
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'
Vue.use(BootstrapVue)
Vue.use(IconsPlugin)
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
```

21:24 까지~ ing







