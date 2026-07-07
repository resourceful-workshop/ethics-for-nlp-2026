---
layout: default
title: Ethics4NLP-2026
---
{% if jekyll.environment  == "production" %}
        {% assign basepath = "." %}
        {%else%}
        {% assign basepath = "" %}
        {% endif %}

# Accepted presentations

## Oral talks

  *  <font size="4"> <b> Title </b> </font>
  [slides](./data/materials/slides.pdf)
  <span style="color:gray"> Authors </span>  
  <button onclick="toggleAbstract('abstract1')">Show abstract</button>  
  <div id="abstract1" class="abstract" style="display:none;">Abstract</div>

  *  <font size="4"> <b> Title </b></font>
  [slides](./data/materials/slides2.pdf)
  <span style="color:gray"> Authors </span>
  <button onclick="toggleAbstract('abstract2')">Show abstract</button>
  <div id="abstract2" class="abstract" style="display:none;">Abstract</div>


<script>
function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    if (abstract.style.display === "none") {
        abstract.style.display = "block";
    } else {
        abstract.style.display = "none";
    }
}
</script>

<script>
  function toggleDisplay(id) {
    var el = document.getElementById(id);
    if (el.style.display === "none" || el.style.display === "") {
      el.style.display = "block";
    } else {
      el.style.display = "none";
    }
  }
</script>
