---
layout: event-point/page
title: Summit Editor
type: logistic
---

In order to support OWASP Leaders and Contributors that want to come to the Summit (see [Participants need support](Participants-need-support.html)) 
the Summit Organization team decided to allocated $20k USD to the concept of 'Summit Editors' (the $20k USD are from [sponsors](../new/sponsors.html) funds)
 
&nbsp;

An Summit Editor is somebody that is going to work hard before the Summit, helping with summit related tasks/activities, in exchange for an 
Summit Ticket and travel expenses.
 
&nbsp;

This is a win-win situation, where the Summit gains more energy/focus and valuable members of the OWASP community are able to participante to the Summit.
 
&nbsp;

In order to make the process fair, the following 'rules of engagement' are proposed:
 
&nbsp;

- Work 4h to 8h per week on Summit tasks and activities
- Proactively take ownership of pending tasks ([from here](https://github.com/OWASP/owasp-summit-2017/projects)) and work on it
- Either:

1. organise at least two Working-Sessions
 - update/create content
 - find participants, help with their questions, help with participants pages (we can help with direct contact and introductions)
 - focus on maximising Workshop potential
 - start working on workshop's objectives (before the summit)
2. help with Summit logistics
 - GitHub content maintenance
 - Site design and jekyll
 - Marketing outreach
 
- Create weekly report entry (with what was done, and pending tasks)
- Probation period of 4 weeks (to see if sponsorship model and is fair (to others that also want sponsorship))




### Selection priority

  - Number of OWASP past contributions (by order of preference)
    - Owasp conferences
    - Owasp projects
    - Owasp chapter
  - Taking Admin tasks to be responsible


### Current Summit Editors

Here is the list of the current Summit Editors. Feel free to contact them for help with the site or Workshop's layout

<ul>
    <ul>
        {% for page in site.pages %}
            {% if page.title and page.role == 'Summit-Editor' %}
                <li><a href="{{page.url}}">{{page.title}}</a></li>
            {% endif %}
        {% endfor %}
    </ul>
</ul>