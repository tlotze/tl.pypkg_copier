{{ "=" * (project_name | length) }}
{{ project_name }}
{{ "=" * (project_name | length) }}

{{ project_description }}

Summary
=======

Features
========

Installation
============

Quick start
===========

Rationale
=========

Concepts
========

Development
===========

Resources:

{%- if source_url %}
  * Source repository: {{ source_url }}
{% endif %}
{%- if github_url %}
  * Github repository: {{ github_url }}
{% endif %}

Acknowledgements
================
