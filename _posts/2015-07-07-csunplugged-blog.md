---
layout: post
tags: 컴퓨터과학-언플러그드 마크다운 공유-협업 xwMOOC
date: 2015-07-07 07:07
thumbnail: img/th-xwMOOC.png
title: 공유와 협업 컴퓨터 과학 언플러그드
published: true
---
### 컴퓨터 과학 언플러그드 3.1 **공유와 협업 버젼**
컴퓨터 과학 언플러그드 버젼 3.1이 발표되었습니다. 인터넷에 대한 내용이 추가되었고, 버젼 3.0에서 Part I, Part II로 양분되었던 것이 하나로 합쳐졌으며, 교육과정이 뉴질랜드 중심에서 글로벌 교육체계에 맞춰 내용이 변경되었고, 로고도 새로이 변경되었습니다. xwMOOC에서 컴퓨터 과학 언플러그드 공유와 협업에 맞도록 새로이 개편했다. 누구나 [마크다운(Markdown)](http://daringfireball.net/projects/markdown/)으로 편하게 코드가 아닌 컴퓨터 과학 언플러그드에만 집중하도록 추진했다.

- [협업과 공유 HTML 버젼](/computationalthinking/unplugged/index.html)
- [컴퓨터과학 언플러그드 한글 저작원본](https://github.com/statkclee/website-csunplugged/)
- [Computer Science Unplugged Version 3.1 PDF 파일](http://csunplugged.org/wp-content/uploads/2015/03/CSUnplugged_OS_2015_v3.1.pdf)

> ### 한국어 프로젝트 참여자 및 원저작자 정보
> 
>한국어 번역: 이광춘  
>한국어 삽화: 문춘경  
>저자: Tim Bell, Ian H. Witten, Mike Fellows  
>실험수업:  Robyn Adams and Jane McKenzie  
>삽화: Matt Powell  

> ### 한글 컴퓨터 과학 언플러그드 버젼 이력
> 
> - ~ 현재 : 진남초 문찬규 교사님 코드닷오알지 내용 바탕 언플러그드 동영상 매핑 작업 진행 중
> - 2015년 07월: 컴퓨터 과학 언플러그드 공유와 협업 버젼 개발
> - 2015년 05월: 컴퓨터 과학 언플러그드 3.1 버젼 한글 번역 완료 HTML/PDF/E-PUB 무료 전자책 배포
>     - 인터넷에 대한 신규 활동 추가, 로고 변경
>     - 버젼 3.0에서 Part I, Part II로 양분되었던 교재(MS 워드)가 하나로 합쳐짐.
>     - 교육과정이 뉴질랜드 중심에서 글로벌 교육체계에 맞춰 변경.
>     - 한국어 언플러그드 교재를 PDF, E-PUB, HTML로 다양화하여 제공. 
> - 2015년 03월: 컴퓨터 과학 언플러그드 3.0 버젼 MS 워드 기반에서 마크다운 공개 소프트웨어 플랫폼 변환(GitHub)
> - 2015년 02월: 컴퓨터 과학 언플러그드 3.0 버젼 삽화 한국화 작업
> - 2015년 01월: 컴퓨터 과학 언플러그드 3.0 버젼 Part IV,V,VI 번역 (MS 워드)
> - 2014년 08월: 컴퓨터 과학 언플러그드 3.0 버젼 Part I,II,III 번역 (MS 워드)

### 공유와 협업 저작 도구 설치

마크다운(Markdown)을 IPython Notebook, R 마크다운에 기반하여 저작을 하고, GitHub에서 Jekyll을 사용하여 HTML 페이지를 
생성하기 때문에 컴퓨터과학 언플러그드 개발 툴체인을 다음과 같이 준비합니다.

1. [Pandoc 설치](http://www.pandoc.org/installing)
2. 파이썬 관련된 팩키지를 설치한다.

~~~
$ pip install -r requirements.txt
~~~
3. 마크다운을 HTML로 변환해서 확인한 후 GitHub에 푸쉬하고 나서 풀요청(Pull Request)을 한다.

~~~
$ make preview
~~~

