Pre Installation
================

* Allocate a server with Docker installed on the OS.
* A sample Docker installation script is provided for installation on Ubuntu.

    ```
    sh docker-install-ubuntu.sh
    ```

* Confirm that Docker containers have internet connectivity in order to update python package dependencies on installation.
* Confirm that the Docker containers have a responsive connection to the related databases and resources and http connectivity to the Dynatrace server.
* The server needs enough RAM / Storage to execute all concurrent queries and operate the OS comfortably. A VM which can be scaled as demand grows is ideal.
* Grant "dynatrace" read-only user / service account on the database access to related objects.
