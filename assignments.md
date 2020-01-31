---
layout: page
title: Assignments
permalink: /assignments/
---

<ul id="archive">
{% for asg in site.assignments reversed %}
      <li class="archiveposturl" style="background: transparent">
        <span><a href="{{ asg.url | prepend: site.baseurl}}">{{ asg.title }}</a></span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right">
<a title="Download problems (pdf)" href="{{ asg.pdf | prepend: site.baseurl }}"><i class="fas fa-file-pdf"></i></a> 
{% if asg.attachment %}
&nbsp; <a title="Download attachments (zip)" href="{{ asg.attachment | prepend: site.baseurl }}"><i class="fas fa-file-archive"></i></a>
{% endif %}
</strong> 
      </li>
{% endfor %}
</ul>


# Get your homeworks from here

* [HomeWork1](./files/CAD_HW_1.pdf)

* [HomeWork2](./files/CAD_HW_2.pdf)

* [HomeWork3](./files/CAD_HW_3.pdf)

* [HomeWork4](./files/CAD_HW_4.pdf)

* [HomeWork5](./files/HW_5.pdf)

* [HomeWork6](./files/HW_6.pdf)

* [HomeWork7](./files/HW_7.pdf)


## [FinalProject](./files/CAD-FinalProject.pdf)