---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all CRM Departments
  version: 1.0.0
  description: Get all crm departments.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/CRM/department/{id}:
    put:
      summary: This method is used to update a single CRM Department record in the
        database. The {id} parameter specifies which CRM Department record to update.
      description: This method is used to update a single crm department record in
        the database. the {id} parameter specifies which crm department record to
        update..
      operationId: CRM_UpdateDepartment
      x-api-path-slug: 3dcartwebapiv1crmdepartmentid-put
      parameters:
      - in: body
        name: department
        description: A Json or XML object containing the new Department
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Department ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - CRM
      - Department
      - Record
      - In
      - Database
      - ""
      - Id
      - Parameter
      - Specifies
      - Which
      - CRM
      - Department
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/CRM/department:
    get:
      summary: Get all CRM Departments
      description: Get all crm departments.
      operationId: CRM_GetAllCRMDepartments
      x-api-path-slug: 3dcartwebapiv1crmdepartment-get
      parameters:
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - CRM
      - Departments
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---