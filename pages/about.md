---
layout: page
title: About
description: 关于本宅
keywords: 可以, 宅, 基, 基地
comments: true
menu: 关于
permalink: /about/
---

我是可以，一个肥宅哦。

喜欢纸皮人。

坚信肥宅有power，有爱世界不孤单。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
