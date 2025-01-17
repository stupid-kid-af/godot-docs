:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the InputEventMouseButton.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_InputEventMouseButton:

InputEventMouseButton
=====================

**Inherits:** :ref:`InputEventMouse<class_InputEventMouse>` **<** :ref:`InputEventWithModifiers<class_InputEventWithModifiers>` **<** :ref:`InputEventFromWindow<class_InputEventFromWindow>` **<** :ref:`InputEvent<class_InputEvent>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Input event type for mouse button events.

Description
-----------

Contains mouse click information. See :ref:`Node._input<class_Node_method__input>`.

Tutorials
---------

- :doc:`Mouse and input coordinates <../tutorials/inputs/mouse_and_input_coordinates>`

Properties
----------

+---------------------------------------------------+------------------------------------------------------------------------+-----------+
| :ref:`MouseButton<enum_@GlobalScope_MouseButton>` | :ref:`button_index<class_InputEventMouseButton_property_button_index>` | ``0``     |
+---------------------------------------------------+------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>`                           | :ref:`double_click<class_InputEventMouseButton_property_double_click>` | ``false`` |
+---------------------------------------------------+------------------------------------------------------------------------+-----------+
| :ref:`float<class_float>`                         | :ref:`factor<class_InputEventMouseButton_property_factor>`             | ``1.0``   |
+---------------------------------------------------+------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>`                           | :ref:`pressed<class_InputEventMouseButton_property_pressed>`           | ``false`` |
+---------------------------------------------------+------------------------------------------------------------------------+-----------+

Property Descriptions
---------------------

.. _class_InputEventMouseButton_property_button_index:

- :ref:`MouseButton<enum_@GlobalScope_MouseButton>` **button_index**

+-----------+-------------------------+
| *Default* | ``0``                   |
+-----------+-------------------------+
| *Setter*  | set_button_index(value) |
+-----------+-------------------------+
| *Getter*  | get_button_index()      |
+-----------+-------------------------+

The mouse button identifier, one of the :ref:`MouseButton<enum_@GlobalScope_MouseButton>` button or button wheel constants.

----

.. _class_InputEventMouseButton_property_double_click:

- :ref:`bool<class_bool>` **double_click**

+-----------+-------------------------+
| *Default* | ``false``               |
+-----------+-------------------------+
| *Setter*  | set_double_click(value) |
+-----------+-------------------------+
| *Getter*  | is_double_click()       |
+-----------+-------------------------+

If ``true``, the mouse button's state is a double-click.

----

.. _class_InputEventMouseButton_property_factor:

- :ref:`float<class_float>` **factor**

+-----------+-------------------+
| *Default* | ``1.0``           |
+-----------+-------------------+
| *Setter*  | set_factor(value) |
+-----------+-------------------+
| *Getter*  | get_factor()      |
+-----------+-------------------+

The amount (or delta) of the event. When used for high-precision scroll events, this indicates the scroll amount (vertical or horizontal). This is only supported on some platforms; the reported sensitivity varies depending on the platform. May be ``0`` if not supported.

----

.. _class_InputEventMouseButton_property_pressed:

- :ref:`bool<class_bool>` **pressed**

+-----------+--------------------+
| *Default* | ``false``          |
+-----------+--------------------+
| *Setter*  | set_pressed(value) |
+-----------+--------------------+
| *Getter*  | is_pressed()       |
+-----------+--------------------+

If ``true``, the mouse button's state is pressed. If ``false``, the mouse button's state is released.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
