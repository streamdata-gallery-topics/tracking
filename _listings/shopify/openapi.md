swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/orders/4528049998/fulfillments/3770145678.json:
    put:
      summary: Update tracking number for a fulfillment.
      description: Update tracking number for a fulfillment..
      operationId: putAdminOrders4528049998Fulfillments3770145678.json
      x-api-path-slug: adminorders4528049998fulfillments3770145678-json-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Tracking
      - Numbera
      - Fulfillment