# ylalz-poc

Follow the [User Guide](https://azure.github.io/Azure-Landing-Zones/accelerator/userguide/)

NOTE:

- Make sure the GitHub account is in correct bill plan. The plan I am using doesn't allow me to create environment protection rule. Therefore I have to diable the feature in Terraform code, which is not ideal.

- The format of platform-landing-zone.tfvars needs more attention. Otherwise the CI pipeline of ylalz-mgmt repository will fail.

- Cannot [disable Azure Monitoring Agent](https://azure.github.io/Azure-Landing-Zones/accelerator/startermodules/terraform-platform-landing-zone/options/ama/) because there is a bug in the Terraform code provided by MS
