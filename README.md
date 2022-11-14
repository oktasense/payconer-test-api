# payconer-test-api
Fake API for testing

To configure the endpoint, visit https://docs.mockend.com/

Basically, create the file .mockend.json:

{
  "ModelName": {
    "fieldName": {
      "<type>": {} | [],
      "hasMany": "Model",
      "belongsTo": "Model"
    }
  }
}
