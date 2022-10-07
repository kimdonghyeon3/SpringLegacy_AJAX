<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
<h3 align="center">Spring Legacy Project - articleList(AJAX 새로운 게시글 불러오기)</h3>

  <p align="center">
    Spring Legacy Project - articleList(AJAX 새로운 게시글 불러오기)
    <br />
    <a href="https://github.com/kimdonghyeon3/ajax_test"><strong>View Demo »</strong></a>
    <br />
    <br />

  </p>
</div>

<hr/>

<!-- ABOUT THE PROJECT -->
## About The Project

![img1](main.png)

Tomcat Legacy Project (Tomcat + Servlet)에서 동작하는 Ajax의 이해를 위한 프로젝트
<br/><br/>
아주 간단한 사이트지만 이런 의문이 들 수 있다.
**"A사용자가 사이트의 게시글을 작성하게 되면, B사용자는 해당 게시글을 언제 볼 수 있을까?"**
<br/><br/>
대부분의 사이트를 둘러보면, A사용자가 글을 썼다면, B사용자의 입장에서는 브라우저를 재랜더링(새로고침)을 통해 새로운 게시물을 파악할 수 있다.
<br/><br/>
**그러면 도대체 새로운 글이 올라왔을 때 울리는 알림은 어떻게 동작을 할까?**
<br/><br/>
 이런 의문에서 시작된 프로젝트로, 최신 글을 불러오는 작업을 ajax를 통해 해결해보자

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

본 프로젝트는 배포 없이 Local에서 작동합니다.

### 설치 방법

**1. Tomcat Download**
   <br>
   http://tomcat.apache.org/

**2. Setting -> Plugins -> SmartTomcat Install**

**3. Edit Configuration -> add new Configuration -> smart tomcat**
   <br/>
   Tomcat Server : 다운받은 톰캣 위치
   <br/>
   Deployment Dir.. : 자신 프로젝트의 src\webapp
   <br/>
   Context Path : /
   <br/>
<br/>
**4. Run**

<p align="right">(<a href="#top">back to top</a>)</p>

## Prject Structure
![img1](structure.png)

<!-- CONTACT -->
## Contact

Email - kimdonghyeon98@gmail.com

Project Link: [https://github.com/kimdonghyeon3/ajax_test](https://github.com/kimdonghyeon3/ajax_test)

<p align="right">(<a href="#top">back to top</a>)</p>


MIT License
Copyright (c) 2021 Othneil Drew

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
