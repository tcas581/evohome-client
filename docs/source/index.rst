Evohome Client
==============

Purpose
-------

The Evohome client provides a straightforward API to allow access to your Evohome data.

Getting started
---------------

You'll need to have signed up for an account at http://www.mytotalconnect.com - you'll use the username and password credentials below.

Install the evohome client library:

.. code-block:: none

    pip install ./evohome-client

Instantiating the client
------------------------

.. code-block:: python

    from evohomeclient import EvohomeClient
    
    client = EvohomeClient('username', 'password')

Contents:

.. toctree::
   :maxdepth: 2

   temperature
   hotwater
   modes

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

