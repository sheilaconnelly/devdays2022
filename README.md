# Implementation Guide publishing and quality control in the cloud

## FHIR Validation with the Firely Terminal GitHub Action
The template repository includes a preconfigured GitHub Action to validate your resources against the FHIR specification and custom validation rules with [Firely Terminal](https://fire.ly/products/firely-terminal/). Any push or pull request to the `main` branch will automatically run the [Firely Validation pipeline](https://github.com/FirelyTeam/firely-terminal-pipeline), containing [bulk validation and custom business rule validation](https://fire.ly/2021/03/04/quality-control-how-to-validate-full-fhir-specifications-in-one-click/) with Firely Terminal.
