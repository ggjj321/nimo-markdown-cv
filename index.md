---
layout: cv
title: Wode "Nimo" Ni
# email:
#   url: mailto:woden@cs.cmu.edu
#   text: woden@cs.cmu.edu
# homepage:
#   url: http://cs.cmu.edu/~woden
#   text: cs.cmu.edu/~woden
---

# 吳克洋

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## 學歷

### **國立臺北科技大學** `2020.9 - 2024.6`

- 資訊工程系學士
- 歷年成績  
  - GPA：3.83/4.0
  - 曾獲一學期書卷獎（3.3％）
  - 總排名系排第 8 名（13％）
- 指導教授：[楊士萱]()教授

## 專案經歷

### **足球自由球自主訓練輔助系統** `2022.7 -`

此系統使用**影像辨識**來偵測足球及球門，結合國家級足球教練的建議，完成一個具有**後端、手機及手錶 App** 的完整軟體系統。

由**楊士萱**教授指導，由吳克洋、李致中兩位學生共同開發完成。

**[後端系統](https://github.com/ggjj321/12-yard-free-throw-server)**
使用 **Docker Compose** 整合 **WebRTC** 、**YOLOv5**、**FastAPI**、**Socket**、**Redis**、**Firebase** 等多項服務，並導入微服務架構進行系統整合。

**[手機 App](https://github.com/ggjj321/12-yard-free-throw-app)**
使用 **Flutter** 進行跨平台開發，搭配後端系統完成一個**跨平台的即時物件辨識手機 App**。


### [**Penrose: From Mathematical Notation to Beautiful Diagrams**](http://penrose.ink/media/Penrose_SIGGRAPH2020.pdf)
Katherine Ye, **Wode Ni**, Max Krieger, Dor Ma'ayan, Joshua Sunshine, Jonathan Aldrich, and Keenan Crane.<br> 
_ACM Transactions on Graphics (SIGGRAPH'20)._<br>
[[PDF](http://penrose.ink/media/Penrose_SIGGRAPH2020.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/siggraph20-penrose.txt)]
[[www](http://penrose.ink/siggraph20.html)]
[[repo](https://github.com/penrose/penrose)]

### [**How Domain Experts Create Conceptual Diagrams and Implications for Tool Design**]({{ page.homepage.url }}/assets/chi-20-natural-diagramming.pdf)

Dor Ma'ayan\*, **Wode Ni\***, Katherine Ye, Chinmay Kulkarni, and Joshua Sunshine.<br>
<i class="fas fa-award"></i> <strong>Best Paper Honourable Mention</strong><br>
_In Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems (CHI'20)._<br>
[[PDF]({{ page.homepage.url }}/assets/chi-20-natural-diagramming.pdf)]
[[BibTeX]({{ page.homepage.url }}/assets/chi-20-natural-diagramming.txt)]

### [**Defining Visual Narratives for Mathematics Declaratively**](http://2019.plateau-workshop.org/assets/papers-2019/9.pdf)

Max Krieger, **Wode Ni**, and Joshua Sunshine.<br>
_Evaluation and Usability of Programming Languages and Tools (PLATEAU 2019), co-located with UIST._<br>
[[PDF](http://2019.plateau-workshop.org/assets/papers-2019/9.pdf)]
[[slides]({{ page.homepage.url }}/assets/plateau-19-presentation.pdf)]

### [**Designing Declarative Language Tutorials: a Guided and Individualized Approach**](http://2019.plateau-workshop.org/assets/papers-2019/2.pdf)

Anael Kuperwajs Cohen, **Wode Ni**, and Joshua Sunshine.<br>
_Evaluation and Usability of Programming Languages and Tools (PLATEAU 2019), co-located with UIST._<br>
[[PDF](http://2019.plateau-workshop.org/assets/papers-2019/2.pdf)]
[[slides]({{ page.homepage.url }}/assets/plateau-19-presentation.pdf)]

---

### [**Substance and Style: domain-specific languages for mathematical diagrams**](https://2017.splashcon.org/event/dsldi-2017-substance-and-style-domain-specific-languages-for-mathematical-diagrams)

**Wode Ni\***, Katherine Ye\*, Joshua Sunshine, Jonathan Aldrich, and Keenan Crane.<br> _Domain-Specific Language Design and Implementation (DSLDI 2017), co-located with SPLASH._ <br>
[[PDF]({{ page.homepage.url }}/assets/dsldi.pdf)]
[[slides]({{ page.homepage.url }}/assets/dsldi-presentation.pdf)]
[[www](http://penrose.ink)]
[[repo](https://github.com/penrose/penrose)]

### [**Whiteboard Scanning Using Super-Resolution**](http://scholar.dickinson.edu/student_honors/221/)

**Wode Ni**.<br> _Dickinson College Honors Theses. Paper 221._<br>
[[PDF]({{ page.homepage.url }}/assets/superres.pdf)]

## Experience
### **Apple** `2022.5 - 2022.9`

_Research Intern - Machine Intelligence_<br>

### **Microsoft Research** `2020.5 - 2020.8`

_Research Intern_<br>
Worked with the [PROSE](https://www.microsoft.com/en-us/research/group/prose/) team (mentored by [Titus Barik](https://www.barik.net/)) on improving developer productivity in Visual Studio Code. I interviewed developers to elicit their needs for code transformation tools in editors. Inspired by the empirical data and relevant work in program synthesis, I designed **reCode**, an interaction model for rapidly performing complex code transformation using the familiar find-and-replace experience.

### **Carnegie Mellon University, Research Experiences for Undergraduate** `2017.5 - 2017.8`

_Research Assistant_<br>
**Penrose** is a system that automatically visualizes mathematics using two domain-specific languages: **Substance** and **Style**. Co-advised by [Jonathan Aldrich](https://www.cs.cmu.edu/~./aldrich/), [Keenan Crane](https://www.cs.cmu.edu/~kmcrane/), [Joshua Sunshine](http://www.cs.cmu.edu/~jssunshi/), and [Katherine Ye](https://www.cs.cmu.edu/~kqy/), I designed and implemented the Style language, and extended the Substance language to support functions and logically quantified statements.

### **Columbia University, Computer Graphics and User Interfaces Lab** `2017.1 - 2017.5`

_Research Assistant_<br>
Worked with prof. Steven Feiner, on **Cyber Affordance Visualization in Augumented Reality** project. Developed a Microsoft Hololens application that visualizes the Columbia campus in AR environment.

## Mentoring

[Hwei-Shin Harriman](https://hsharriman.github.io/) (Olin College of Engineering, independent research) `CMU, 2021 - Now` <br>
[Helena Yang](https://heleaf.me/) (CMU, [REUSE](https://www.cmu.edu/scs/s3d/reuse/)) `CMU, 2021` <br>
[Max Krieger](https://a9.io/) (CMU, independent research & [REUSE](https://www.cmu.edu/scs/s3d/reuse/)) `CMU, 2018 - 2021` <br>
[Courtney Miller](https://courtney-e-miller.github.io/) (New College of Florida, [REUSE](https://www.cmu.edu/scs/s3d/reuse/)) `CMU, 2019` <br>
[Anael Kuperwajs Cohen](https://anaelkuperwajs.github.io/) (Macalester College, [REUSE](https://www.cmu.edu/scs/s3d/reuse/)) `CMU, 2019` <br>

---

## Honors & Awards

CHI'20 Best Paper Honourable Mention Award `CMU, 2020` <br>
Phi Beta Kappa `Dickinson, 2018` <br>
Excellence in Computer Science Award `Columbia, 2018` <br>
Travel Award PL Mentoring Workshop (PLMW) `SPLASH, 2018` <br>
Tau Beta Pi, Engineering Honor Society `Columbia, 2017` <br>
Computer Science Departmental Honors `Dickinson, 2016` <br>
Pi Mu Epsilon, Mathematics Honor Society `Dickinson, 2016` <br>
Upsilon Pi Epsilon, Computer Science Honor Society `Dickinson, 2016` <br>
Alpha Lambda Delta, First year Honor Society `Dickinson, 2013`<br>
John Montgomery Scholarship `Dickinson, 2013` <br>

## Teaching

Teaching Assistant, **Foundations of Software Engineering (17-313)** `CMU, 2022` <br>
Teaching Assistant, **Crafting Software (17-450/17-950)** `CMU, 2022` <br>
Teaching Assistant, **Programming Languages and Translators (COMS 4115)** `Columbia, 2017 - 2018` <br>
Teaching Assistant, **Introduction to Java II (COMP 132)** `Dickinson, 2016` <br>
Peer Tutor, **Data Structures and Problem Solving (COMP 232)** `Dickinson, 2016` <br>
Computer Lab Consultant `Dickinson, 2014 - 2016` <br>


## Service

Sub-reviewer `OOPSLA'21, VL/HCC'21` <br>
Reviewer `CHI'21, CHI'22, SIGGRAPH'22` <br>
Research Experiences for Undergraduates in Software Engineering Admission Committee `CMU, 2019 - 2022` <br>

<!-- ### Footer

Last updated: May 2013 -->
