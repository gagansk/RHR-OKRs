Background
==========

.. _roles:

Roles
-----

The diagram below shows the roles associated with OKRs within the OCTO with names of the people assigned to them. These roles are explained in the OKR Practice in the CTO Office. The Red Hat Research Group has identified the new KR Shepherd role.  Hence this is the only role that will be explained in detail within this document.

PnT LeaderShip
--------------

The President of the PnT organization plus all associated org leads, including the CTO.

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

