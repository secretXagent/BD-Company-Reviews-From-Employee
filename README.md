# BD Software Industry Bad Company Experiences Repository
Welcome to the BD Software Industry Bad Company Experiences Repository. This repository is a space where individuals can share their negative experiences with companies in the BD software industry, along with legal proof to support their claims.

## Contributions

Please see below for a list of contributions to this repository. To read more about a specific contribution, simply click on the corresponding link.

{% for file in site.github.public_repositories[0].source.files %}
  {% if file.path contains 'experiences/' %}
  ### [{{ file.path | split:'/' | last | split:'.' | first }}]({{ file.html_url }})

  {{ file.decoded_content | remove: '<p>' | remove: '</p>' }}
  {% endif %}
{% endfor %}


## How to contribute
To contribute to this repository, please follow the steps outlined in the README file.

## Code of conduct
To ensure that this repository remains a safe and supportive space for everyone to share their experiences, we have established a code of conduct. Please review the code of conduct before contributing, and make sure to follow the guidelines outlined therein.

## Disclaimer
Please note that the information in this repository is provided by individual contributors and may not necessarily reflect the views or opinions of the repository maintainers. We do not endorse or condone any illegal activity, and any contributions that violate our code of conduct or that contain false or misleading information will be removed.

If you have any questions or concerns, please feel free to contact the repository maintainers. Thank you for contributing to this important initiative.
