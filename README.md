# Microsoft Fabric APIs Specification

Welcome to the Microsoft Fabric APIs Specification repository. This repository is dedicated to providing developers with a comprehensive, organized, and easily accessible collection of API specifications for Microsoft Fabric. These specifications are designed to enable developers to effectively utilize and integrate Microsoft Fabric's public APIs into their applications and services.

## Overview

This repository serves as a comprehensive collection of API specifications for Microsoft Fabric. These specifications provide developers with essential details required to interact with Fabric's public APIs. Each API is documented in Swagger (OpenAPI) JSON format to ensure ease of use and compatibility with various tools and platforms.

## SDK Generation

The Fabric APIs SDK utilizes the [Autorest client library generator](https://github.com/Azure/autorest) package to generate the SDKs. The Swagger specifications provided here are designed to align with the capabilities and best practices that Autorest offers. However, developers are at liberty to use any generator that meets their specific requirements. The choice of generator is left to the developers, based on factors such as completeness, readiness, and other relevant metrics.

## API Documentation

For detailed information on utilizing the Fabric APIs, please refer to the official documentation available at [Microsoft Fabric REST API documentation](https://learn.microsoft.com/en-us/rest/api/fabric).
Some swagger specification contain the `x-ms-fabric-sdk-long-running-operation` tag. This tag is used to denote long running operations in Fabirc APIs. More information regarding this tag is available in: [Long running operations](https://learn.microsoft.com/en-us/rest/api/fabric/articles/long-running-operation)

## License

This project is licensed under the MIT License. Please refer to the [LICENSE](LICENSE.txt) file for more details.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
