Modules
-------

.. raw:: html

   <dl>
   <dt>

routes/Beneficiario

.. raw:: html

   </dt>
   <dd><p>

Archivo para definir las rutas de la entidad beneficiarios

.. raw:: html

   </p>
   </dd>
   <dt>

routes/departamentos

.. raw:: html

   </dt>
   <dd><p>

Archivo para definir las rutas de la entidad departamentos

.. raw:: html

   </p>
   </dd>
   <dt>

routes/establecimientos\_salud

.. raw:: html

   </dt>
   <dd><p>

Archivo para definir las rutas de la entidad establecimientos\_salud

.. raw:: html

   </p>
   </dd>
   <dt>

routes/inscripciones

.. raw:: html

   </dt>
   <dd><p>

Archivo para definir las rutas de la entidad inscripciones

.. raw:: html

   </p>
   </dd>
   <dt>

routes/titulares

.. raw:: html

   </dt>
   <dd><p>

Ruta para el manejo de REST de titulares

.. raw:: html

   </p>
   </dd>
   </dl>

routes/Beneficiario
-------------------

Archivo para definir las rutas de la entidad beneficiarios

**Author:** Juan C Choque jchoque@agetic.com.bo

-  `routes/Beneficiario <#module_routes/Beneficiario>`__

   -  \_static\_

      -  `.madres <#module_routes/Beneficiario.madres>`__
      -  `.validacionBeneficiarios <#module_routes/Beneficiario.validacionBeneficiarios>`__
      -  `.buscaAtributosUno <#module_routes/Beneficiario.buscaAtributosUno>`__
      -  `.Personascreate <#module_routes/Beneficiario.Personascreate>`__

   -  \_inner\_

      -  `~routes/Beneficiario <#module_routes/Beneficiario..routes/Beneficiario>`__
      -  `~routes/Beneficiario <#module_routes/Beneficiario..routes/Beneficiario>`__

routes/Beneficiario.madres
~~~~~~~~~~~~~~~~~~~~~~~~~~

ruta de madres

| **Tipo**: static property of
\ `routes/Beneficiario <#module_routes/Beneficiario>`__\ 
| 

routes/Beneficiario.validacionBeneficiarios
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Este segmento de codigo sirve para validacion de beneficiarios

| **Tipo**: static property of
\ `routes/Beneficiario <#module_routes/Beneficiario>`__\ 
| 

routes/Beneficiario.buscaAtributosUno
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Este segmento busca atributos

| **Tipo**: static property of
\ `routes/Beneficiario <#module_routes/Beneficiario>`__\ 
| 

routes/Beneficiario.Personascreate
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

crea personas

| **Tipo**: static property of
\ `routes/Beneficiario <#module_routes/Beneficiario>`__\ 
| 

routes/Beneficiario~routes/Beneficiario
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Busca la lista de beneficiarios

| **Tipo**: inner property of
\ `routes/Beneficiario <#module_routes/Beneficiario>`__\ 
| 

routes/Beneficiario~routes/Beneficiario
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Destruye a un beneficiario

| **Tipo**: inner property of
\ `routes/Beneficiario <#module_routes/Beneficiario>`__\ 
| 

routes/departamentos
--------------------

Archivo para definir las rutas de la entidad departamentos

routes/establecimientos\_salud
------------------------------

Archivo para definir las rutas de la entidad establecimientos\_salud

-  `routes/establecimientos\_salud <#module_routes/establecimientos_salud>`__

   -  `~route\_establecimientos <#module_routes/establecimientos_salud..route_establecimientos>`__
   -  `~establecimientosSalud\_finAll <#module_routes/establecimientos_salud..establecimientosSalud_finAll>`__
   -  `~EstablecimientosSalud <#module_routes/establecimientos_salud..EstablecimientosSalud>`__
      : string

routes/establecimientos\_salud~route\_establecimientos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ruta para el manejo de establecimientos

| **Tipo**: inner property of
\ `routes/establecimientos\_salud <#module_routes/establecimientos_salud>`__\ 
| 

routes/establecimientos\_salud~establecimientosSalud\_finAll
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Método para buscar todos los establecimientos de salud

| **Tipo**: inner property of
\ `routes/establecimientos\_salud <#module_routes/establecimientos_salud>`__\ 
| 

routes/establecimientos\_salud~EstablecimientosSalud : string
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

| **Tipo**: inner constant of
\ `routes/establecimientos\_salud <#module_routes/establecimientos_salud>`__\ 
| 

routes/inscripciones
--------------------

Archivo para definir las rutas de la entidad inscripciones

routes/titulares
----------------

Ruta para el manejo de REST de titulares

**Author:** Juan Perez jperez@agetic.com.bo

+---------+----------+------------------------+
| Param   | Type     | Description            |
+=========+==========+========================+
| \_id    | string   | Id of bonus document   |
+---------+----------+------------------------+

-  `routes/titulares <#module_routes/titulares>`__

   -  `~/api/v1/titulares <#module_routes/titulares../api/v1/titulares>`__
   -  `~/api/v1/titulares/:id <#module_routes/titulares../api/v1/titulares/_id>`__
   -  `~/api/v1/titulares - [GET](req,
      res) <#module_routes/titulares../api/v1/titulares%20-%20[GET]>`__
   -  `~/api/v1/titulares - [POST](req,
      res) <#module_routes/titulares../api/v1/titulares%20-%20[POST]>`__
   -  `~/api/v1/titulares/:id - [PUT](req,
      res) <#module_routes/titulares../api/v1/titulares/_id%20-%20[PUT]>`__
   -  `~/api/v1/titulares/:id - [GET](req,
      res) <#module_routes/titulares../api/v1/titulares/_id%20-%20[GET]>`__
   -  `~/api/v1/titulares/:id - [DELETE](req,
      res) <#module_routes/titulares../api/v1/titulares/_id%20-%20[DELETE]>`__

routes/titulares~/api/v1/titulares
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Rutas para titulares

| **Tipo**: inner property of
\ `routes/titulares <#module_routes/titulares>`__\ 
| 

routes/titulares~/api/v1/titulares/:id
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Rutas para titulares

**Tipo**: inner property of
\ `routes/titulares <#module_routes/titulares>`__\ 

+---------+-----------+-----------------------------+
| Param   | Type      | Description                 |
+=========+===========+=============================+
| id      | integer   | Identificador del titular   |
+---------+-----------+-----------------------------+

routes/titulares~/api/v1/titulares - `GET <req,%20res>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Método GET para titulares

**Tipo**: inner method of
\ `routes/titulares <#module_routes/titulares>`__\ 

+---------+----------+---------------+
| Param   | Type     | Description   |
+=========+==========+===============+
| req     | object   | Request       |
+---------+----------+---------------+
| res     | object   | Response      |
+---------+----------+---------------+

routes/titulares~/api/v1/titulares - `POST <req,%20res>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Metodo POST para titulares

**Tipo**: inner method of
\ `routes/titulares <#module_routes/titulares>`__\ 

+---------+----------+---------------+
| Param   | Type     | Description   |
+=========+==========+===============+
| req     | object   | Request       |
+---------+----------+---------------+
| res     | object   | Response      |
+---------+----------+---------------+

routes/titulares~/api/v1/titulares/:id - `PUT <req,%20res>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Método PUT para titulares

**Tipo**: inner method of
\ `routes/titulares <#module_routes/titulares>`__\ 

+---------+----------+---------------+
| Param   | Type     | Description   |
+=========+==========+===============+
| req     | object   | Request       |
+---------+----------+---------------+
| res     | object   | Response      |
+---------+----------+---------------+

routes/titulares~/api/v1/titulares/:id - `GET <req,%20res>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Método GET para titulares

**Tipo**: inner method of
\ `routes/titulares <#module_routes/titulares>`__\ 

+---------+----------+---------------+
| Param   | Type     | Description   |
+=========+==========+===============+
| req     | object   | Request       |
+---------+----------+---------------+
| res     | object   | Response      |
+---------+----------+---------------+

routes/titulares~/api/v1/titulares/:id - `DELETE <req,%20res>`__
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Método DELETE para titulares

**Tipo**: inner method of
\ `routes/titulares <#module_routes/titulares>`__\ 

+---------+----------+---------------+
| Param   | Type     | Description   |
+=========+==========+===============+
| req     | object   | Request       |
+---------+----------+---------------+
| res     | object   | Response      |
+---------+----------+---------------+

