rest_controller_generators
==========================

Generators for creating RESTfull controllers in Rails

### Description
Create a Rails RESTful controller.

Expects an ApiController to exist in the same namespace

### Example
    `rails generate rest_controller Api::V2::Things name description`

Generates:
`app/controllers/api/v2/things_controller.rb`

with :name and :description as whitelisted params
