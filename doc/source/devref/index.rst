..
      Copyright 2010-2011 United States Government as represented by the
      Administrator of the National Aeronautics and Space Administration.
      All Rights Reserved.

      Licensed under the Apache License, Version 2.0 (the "License"); you may
      not use this file except in compliance with the License. You may obtain
      a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
      WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
      License for the specific language governing permissions and limitations
      under the License.

Developer Guide
===============

In the Developer Guide, you will find information on Neutron's lower level
programming APIs. There are sections that cover the core pieces of Neutron,
including its database, message queue, and scheduler components. There are
also subsections that describe specific plugins inside Neutron. Finally,
the developer guide includes information about Neutron testing infrastructure.


Programming HowTos and Tutorials
--------------------------------
.. toctree::
    :maxdepth: 3

    development.environment
    contribute
    neutron_api
    sub_projects
    client_command_extensions


Neutron Internals
-----------------
.. toctree::
   :maxdepth: 3

   services_and_agents
   api_layer
   api_extensions
   plugin-api
   db_layer
   rpc_api
   layer3
   l2_agents
   advanced_services
   oslo-incubator
   callbacks

Testing
-------
.. toctree::
   :maxdepth: 3

   fullstack_testing

Module Reference
----------------
.. toctree::
   :maxdepth: 3

.. todo::

    Add in all the big modules as automodule indexes.


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
