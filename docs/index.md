
# Labs
{% for lab in site.data.labs %}
* [{{lab.name}}](https://colab.research.google.com/github/mim-uw/rl-2023-24/blob/main/docs/{{lab.file}})
{% endfor %}

# Homeworks
{% for homework in site.data.homeworks %}
* [{{homework.name}}](https://colab.research.google.com/github/mim-uw/rl-2023-24/blob/main/docs/{{homework.file}})
{% endfor %}
