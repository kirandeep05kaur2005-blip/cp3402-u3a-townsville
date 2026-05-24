# CP3402 Supplementary Assignment – U3A Townsville

## Project Overview

This project is a WordPress website developed for U3A Townsville as part of the CP3402 Supplementary Assignment.

The website was created using WordPress with the Astra parent theme and a custom Astra Child theme.

The website provides information about:

* U3A Townsville
* Courses and activities
* Membership
* Community participation
* Contact information

---

## Technologies Used

* WordPress
* Astra Theme
* Astra Child Theme
* Docker
* GitHub
* HTML
* CSS

---

## Local Development Environment

This project uses Docker for local development.

### Run the project

```bash
docker-compose up -d
```

Open in browser:

```text
http://localhost:8080
```

---

## Child Theme Changes

The Astra Child theme includes:

* Custom colours
* Button styling
* Typography improvements
* Footer styling
* Layout adjustments

Files modified:

* style.css
* functions.php

---

## Deployment Workflow

The project uses GitHub for version control.

Changes are committed locally and pushed to GitHub regularly using meaningful commit messages.

---

## Developer Notes

The project structure includes:

```text
astra-child/
README.md
REPORT.md
docker-compose.yml
```

Further changes to the child theme can be made inside:

* style.css
* functions.php
