# design-first-demo

The code is use to demontrate how we can use [SwaggerHub](https://swagger.io/tools/swaggerhub/) to design and API and automaticatlly update a 3Scale Api Gateway upon a Pull Request merge.


## Requirement.

1. A 3Scale installation
1. The [SwaggerHub API code](https://app.swaggerhub.com/apis/froberge/CoffeeShop-API/1.0.0-SHAPSHOT)
1. A Fork of this repository.
1. Define the 3 secrets needed to run the Workflow
    * DEVKEY_TOKEN
    * THREESCALE_DOMAIN
    * THREESCALE_TOKEN
    
![workflow image](/doc/images/secretpage.png)
