---
layout: defaults/page
permalink: index.html
narrow: true
title: \Início 
---

## O que eu faço 

<!---{% include components/intro.md %}
[Here's the full feature list and some quick examples of what it can do.]({{ site.baseurl}}{% link _pages/about.md %})
--->

Estudante de doutorado em Ciências pelo Instituto de Biofísica Carlos Chagas Filho, pelo Laboratório de Radioisótopos (UFRJ), com o projeto de tese intitulado: "Avaliação dos impactos ecotoxicológicos relacionados aos rompimentos das barragens de Fundão (Mariana-MG) e Barragem I da mina do córrego do Feijão (Brumadinho-MG)".
[+ info]({{ site.baseurl}}{% link _pages/about.md %})

<hr />

## What I do

PhD student at Federal University of Rio de Janeiro with the project: "Investigating the ecotoxicological impacts related to the dam ruptures in Mariana (MG) and Brumadinho (MG), Brazil". 
[+ info]({{ site.baseurl}}{% link _pages/about.md %})

<hr />

<!---
This web site is the documentation for the theme and also provides examples of how you can use and modify it. TIt is built using Friday Theme directly from the [GitHub repo](https://github.com/sfreytag/friday-theme) and published to GitHub pages.

[The documentation]({{ site.baseurl }}{% link list/projects.md %}) covers the basics of installing and using it, and is an example of how you could write documentation about your own projects.

[The blog]({{ site.baseurl }}{% link list/posts.html %}) has a bunch of tips about how to use Friday Theme. These show how the blog works, including the tags. There's the three most-recent posts below included below.

<hr />
--->

### Postagens recentes

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


