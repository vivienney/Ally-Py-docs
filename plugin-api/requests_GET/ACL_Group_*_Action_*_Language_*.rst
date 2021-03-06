.. _reuqest-GET-ACL/Group/*/Action/*/Language/*:

**ACL/Group/*/Action/*/Language/***
==========================================================

* Use the HTTP **GET** method
* The request is defined by API call ``internationalization.language.api.language.ILanguageService.getById``

  
* The request will GET a model :ref:`entity-internationalization.language.api.language.Language`

::

   Provides the entity based on the identifier.
   
   @param identifier: object
       The id of the entity to find.


URL parameters
-------------------------------------
Each entry matches a **\*** in their respective order.

* The unique identifier **Group.Name** from :ref:`entity-acl.api.group.Group`.
* The unique identifier **Action.Path** from :ref:`entity-gui.action.api.action.Action`.
* The unique identifier **Language.Code** from :ref:`entity-internationalization.language.api.language.Language`.


Query parameters
-------------------------------------
There are no query parameters available for this request except for global :ref:`headers_parameters`.
