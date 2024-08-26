---
title: Bombay Favourites
author: Karen
layout: imtf
---

<section class='section'>

<h2 class="title"> All the recipes, for now </h2>
<div class='grid'>
{% for recipe in site.recipes %}
    <div class="cell">
<a href="{{ recipe.url }}">
{{ recipe.title }}</a></div>
{% endfor %}
</div>

</section>

<section class="section">
 <h2 class="title">Barbecue</h2>
 <div class="grid">
    <div class="cell">Boti Kebab</div>
    <div class="cell">Chicken Tikka</div>
    <div class="cell">Corn Kabab</div>
    <div class="cell">Murgh Malai Kabab</div>
    <div class="cell">Seekh Kabab</div>
    <div class="cell">Tandoori Chicken</div>
    <div class="cell">Tandoori Prawn</div>
    <div class="cell">Tamarind Chutney</div>
    <div class="cell">Pudina Chutney</div>
 </div>
</section>
<section class="section">
 <h2 class="title">Cakes</h2>
 <div class="grid">
    <div class="cell">Black Forest Cake</div>
    <div class="cell">Carrot Cake</div>
    <div class="cell">Chocolate</div>
    <div class="cell">Fruit Cake (Dark)</div>
    <div class="cell">Fruit Cake (Light)</div>
    <div class="cell">Coconut Thali</div>
 </div>
</section>
