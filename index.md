---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
page-intro-headline: Hello, My name is designer
page-intro: I love design and other artsy things like design. I like pizza, too. I like to design tasty pizzas
---



Hello!

{% include components/page-intro.html
    page-intro-headline=page.page-intro-headline
    page-intro=page.page-intro
%}


