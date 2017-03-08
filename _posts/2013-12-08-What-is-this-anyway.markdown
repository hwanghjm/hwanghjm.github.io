---
title: Ruby on jekyll 구현
date: 2013-12-08 19:55:16
categories: jekyll testing
---


블로그 만들기 세미나


### 소개

1. github에서 제공하는 서비스를 이용
2. Ruby와 jekyll을 사용
3. github 란?
* 버전 관리 툴인 GitHub(깃허브)는 GIt(깃)을 사용하는 프로젝트를 웹호스팅하는 서비스
* Ruby on Rails로 작성, open source

### Screenshots

![screenshot]({{ site.baseurl }}/images/herring cove.png)

### Git 설치

1. https://git-scm.com/download/win 에서 윈도우용 Git 을 설치하여 사용할 수 있다.
2. Git 에 대한 사용방법 및 용어에 대해 알고 싶다면 아래 URL 을 참고할 것
   [https://rogerdudler.github.io/git-guide/index.ko.html](https://rogerdudler.github.io/git-guide/index.ko.html)
3. Github desktop 을 설치하여 편리하게 이용하자
   [https://desktop.github.com](https://desktop.github.com)
4. github 에 계정을 만들자.
5. Repository 를 만드는 데 다음을 참고하여 만들자.
   [https://pages.github.com/](https://pages.github.com/)
6. 이제 자신의 사이트를 호스팅할 수 있는 준비는 완료되었다.

### 개발 툴 고르기
1. 현재 유행하고 있는 sublime text
   [https://www.sublimetext.com/3](https://www.sublimetext.com/3)
2. 그다음으로 인기있는 GitHub 에서 open source 로 만들어진 Atom
   [https://atom.io/](https://atom.io/)
3. Visual Studio Code 도 있음
   [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
4. 다 비슷하니 아무거나 설치

### Ruby + Jekyll 설치
1. Ruby 와 Ruby Devkit 을 다운받자.
   [https://rubyinstaller.org/downloads/](https://rubyinstaller.org/downloads/)
2. Ruby Devkit 설치
   cd {download dir}
   ruby dk.rb init
   ruby dk.rb install
3. Jekyll 환경 설정
   gem install jekyll bundler
   bundle install
4. 사이트 호스팅
   bundle exec jekyll serve

### 포트폴리오 사이트 구현
1. Jekyll theme 에서 제공하는 것 중 마음에 드는 것을 골라보자.
   [https://jekyllthemes.io/](https://jekyllthemes.io/)
2. freelancer 로 선택
   [https://jeromelachaud.github.io/freelancer-theme/](https://jeromelachaud.github.io/freelancer-theme/)
3. 소스를 다운받고 bundle install 실행
   "Could not locate Gemfile or .bundle/ directory" 에러 발생하면 Gemfile 을 만들고 아래 내용 추가
     source "https://rubygems.org"
     gem 'github-pages'
4. 호스팅
    bundle exec jekyll serve
5. _config.yml 변경
   각자 알아서..
6. github 에 반영
   github desktop 으로 commit 후 sync 하면 호스팅된 것을 확인할 수 있음



### Download

[download](https://github.com/arnp/herring-cove/archive/master.zip)

