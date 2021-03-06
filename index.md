---
title: NUCCDC
---

## What is CCDC?
The [Collegiate Cyber Defense Competition][ccdc] is an annual [red-team vs. blue-team][redblue] competition between colleges and universities in the United States.

The competition is split into various regions across the US, and our team is part of the [Northeast region][ne-region].

[ccdc]: https://www.nationalccdc.org/
[redblue]: https://securitytrails.com/blog/cybersecurity-red-blue-team
[ne-region]: https://neccdl.org/neccdc/

## The Team
Our team consists of students from many diverse backgrounds and fields of expertise.

<table>
  <tbody>
  {% for member in site.data.members %}
    <tr>
      <td>
        <img class="face" src="https://github.com/{{member.github}}.png?size=100"/>
      </td>
      <td>{{member.name}}</td>
      <td>
        {{member.desc | markdownify}}
      </td>
    </tr>
  {% endfor %}
  </tbody>
</table>


## How do I join?

We're glad you're interested in joining the team!

We have an annual tryout process which takes place between the end of September and early November.  The CCDC competition starts early in the spring semester.
Everyone is welcome to try out -- graduates and undergraduates, as well as international students.

You can obtain more information regarding CCDC (including tryouts) and our partner club, NU Security Club, by joining the [NUSec mailing list][mailing-list].

[mailing-list]: http://eepurl.com/gDtvtb
