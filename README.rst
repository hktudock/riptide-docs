|Riptide|
=========

.. |Riptide| image:: https://riptide-docs.readthedocs.io/en/latest/_images/logo.png
    :alt: Riptide

.. class:: center

    ======================  ===================  ===================  ===================
    *Main packages:*        lib_                 proxy_               cli_
    *Container-Backends:*   engine_docker_
    *Database Drivers:*     db_mysql_            db_mongo_
    *Plugins:*              php_xdebug_
    *Kubernetes:*           k8s_client_          k8s_controller_
    *Related Projects:*     configcrunch_
    *More:*                 **docs**             repo_                docker_images_
    ======================  ===================  ===================  ===================

.. _lib:            https://github.com/Parakoopa/riptide-lib
.. _cli:            https://github.com/Parakoopa/riptide-cli
.. _proxy:          https://github.com/Parakoopa/riptide-proxy
.. _configcrunch:   https://github.com/Parakoopa/configcrunch
.. _engine_docker:  https://github.com/Parakoopa/riptide-engine-docker
.. _db_mysql:       https://github.com/Parakoopa/riptide-db-mysql
.. _db_mongo:       https://github.com/Parakoopa/riptide-db-mongo
.. _docs:           https://github.com/Parakoopa/riptide-docs
.. _repo:           https://github.com/Parakoopa/riptide-repo
.. _docker_images:  https://github.com/Parakoopa/riptide-docker-images
.. _php_xdebug:     https://github.com/Parakoopa/riptide-plugin-php-xdebug
.. _k8s_client:     https://github.com/Parakoopa/riptide-k8s-client
.. _k8s_controller: https://github.com/Parakoopa/riptide-k8s-controller

|docs| |slack|

.. |docs| image:: https://readthedocs.org/projects/riptide-docs/badge/?version=latest
    :target: https://riptide-docs.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. |slack| image:: https://slack.riptide.parakoopa.de/badge.svg
    :target: https://slack.riptide.parakoopa.de
    :alt: Join our Slack workspace

Riptide is a set of tools to manage development environments for web applications.
It's using container virtualization tools, such as `Docker <https://www.docker.com/>`_
to run all services needed for a project.

It's goal is to be easy to use by developers.
Riptide abstracts the virtualization in such a way that the environment behaves exactly
as if you were running it natively, without the need to install any other requirements
the project may have.

Documentation
-------------

This repository contains the documentation for all components listed above.

The rendered documentation can be found at `Read the Docs <https://riptide-docs.readthedocs.io/en/latest/>`_.