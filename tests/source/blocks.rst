============
Math Example
============

Formula 1
   Definition of the formula as inline math:
   :math:`\frac{ \sum_{t=0}^{N}f(t,k) }{N}`.

   Some more text related to the definition.


Display math:

.. math::

      \frac{ \sum_{t=0}^{N}f(t,k) }{N}


============
Code Example
============

>>> print("this is a Doctest block.")
this is a Doctest block.


==========
Line Block
==========

| text
  sub text
| more text
|
|


Other text
----------

other text


Referencing terms from a glossary
---------------------------------

Some other text that refers to :term:`Glossary2-Term2`.


Http domain directive
---------------------

.. http:get:: /users/(int:user_id)/posts/(tag)
