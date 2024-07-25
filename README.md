# Aropä - a student peer review system

Aropä is a system supporting student peer review. It was hosted at the University of Glasgow
from January 2010 until July 2024, and made available free of charge to institutions across the world.

During that time over 76,000 students used the system in developing their writing and critical review skills.
It helped more than 300 instructors in almost 60 institutions facilitate the peer-review process in over 3,350 assignments
(approximately five assignments per week).

It has supported instructors with such issues as randomisation, group submissions, labelled submissions,
review marking and flexible rubric creation as well as providing a range of administrative features including
extensions, outlier elimination and report creation.

Aropä was provided on a wholly voluntary basis by two academics (Prof. Helen Purchase and Dr. John Hamer).

# Running w/ Docker

1. Clone this repository
    ```git clone https://github.com/JohnHamer-Glasgow/aropa.git```
2. Make that directory the current one
    ```cd aropa```
3. Build the image
     ```docker compose build```
4. Copy the docker config to local config.  Make any changes you like to
   app/docker-config.php (it should run without any changes)
     ```cp app/docker-config.php app/local-config.php```
5. Start the container
     ```docker compose up```

## Selected Publications

* Purchase, H.C. and Hamer, J (2018). Perspectives on peer-review: eight years of Aropä,
  _Assessment & Evaluation in Higher Education_ 43(3), pp473-487, <https://www.tandfonline.com/doi/abs/10.1080%2F02602938.2017.1359819>
* Purchase, H.C. and Hamer, J (2018). Peer-review in practice: eight years of Aropä,
  _Assessment & Evaluation in Higher Education_ 43(7), pp1146-1165, <https://www.tandfonline.com/doi/abs/10.1080%2F02602938.2018.1435776>
* Purchase, H.C. and Hamer, J (2024). Trends in practical student peer-review, <https://arxiv.org/abs/2401.00980>
