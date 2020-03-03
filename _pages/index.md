---
title: Xiaojun Chang
layout: default
excerpt: Home page of Xiaojun Chang's website
permalink: /
---

| <a href="mailto:cxj273@gmail.com" target="_blank" style="text-align:center; display:block"><i class="fa fa-envelope ai-3x"></i></a> | <a href="{{ site.google_scholar_url }}" target="_blank" style="text-align:center; display:block"><i class="ai ai-google-scholar-square ai-3x"></i></a> | <a href="https://linkedin.com/in/{{ site.linkedin_username }}" target="_blank" style="text-align:center; display:block"><i class="fa fa-linkedin ai-3x"></i></a> | <a href="https://github.com/{{ site.github_username }}" target="_blank" style="text-align:center; display:block"><i class="fa fa-github ai-3x"></i></a> |

<br/>

<img class="profile-picture" src="{{site.url}}{{site.baseurl}}/images/profile-picture/profile_picture.jpg" />

Greetings! I am a faculty member at Faculty of Information Technology, Monash University Clayton Campus, Australia. I am also affiliated with Monash University Centre for Data Science. I am ARC Discovery Early Career Researcher Award (DECRA) Fellow between 2019-2021 (awarded in 2018). I am actively looking for talented and motivated PhD students to work with me. Please drop me an email if you are interested.

Before joining Monash, I was a Postdoc Research Associate in School of Computer Science, Carnegie Mellon University, working with [Prof. Alex Hauptmann](http://www.cs.cmu.edu/~alex/){:target="_blank"}. I have spent most of my time working on exploring multiple signals (visual, acoustic, textual) for automatic content analysis in unconstrained or surveillence videos. Our system has achieved top performance in various international competitions, such as TRECVID MED, TRECVID SIN, and TRECVID AVS.

I received my Ph.D. degree in Centre for Artificial Intelligence & Faculty of Engineering and Information Technology, University of Technology Sydney, under the supervision of [Prof. Yi Yang](http://www.cs.cmu.edu/~yiyang/){:target="_blank"}. During my PhD study, I was sequentially mentored by Prof. [Feiping Nie](http://www.escience.cn/people/fpnie/){:target="_blank"} and [Yaoliang Yu](https://cs.uwaterloo.ca/~y328yu/){:target="_blank"}. My research focus in this period was mainly on developing machine learning algorithms and apply them to multimedia analysis and computer vision.

## Research Interests

My general research interest is to develop structured machine learning models for computer vision and multimedia tasks. I mainly investigate how to explore the information contained in videos and develop the advanced artificial intelligence systems. Recently, I focus on the following topics, include:

- Video Analysis, including event detection, object detection, segmentation.

- Learning with Limited Supervision, including few-shot learning, zero-shot learning.

- Visual Navigation, including vision-language navigation, and vision-and-dialog navigation.

## News

<table>
{% for article in site.data.news %}
<tr>
{% include news.html %}
</tr>
{% endfor %}
</table>
