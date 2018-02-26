kibana
=========

A simple ansible role to install and configure kibana

Requirements
------------

No special requirements

Role Variables
--------------

* KIBANA_VERSION: The version of kibana to install (default is 6.2.2)
* KIBANA_HOST: The default host used to bind kibana to it (default is 127.0.0.1)
* KIBANA_PORT: The default port that kibana listens on it (default is 5601)
* KIBANA_ELASTIC_URL: The URL of elasticsearch server that kibana connects to it (default is http://localhost:9200)


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: mohsensy.kibana, KIBANA_VERSION: 6.2.2, KIBANA_PORT: 5600 }

License
-------

BSD

Author Information
------------------

If you have any question please contact me on

[twitter](https://twitter.com/mouhsen_ibrahim)

[linkedin](https://linkedin.com/in/mohsen-ibrahim-670b13112/)

email mohsen47@hotmail.co.uk
