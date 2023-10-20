# My Day 2 Project: Securing My Web Application with SSL Certificates (Azure Premium and GoDaddy Domain Version)

Today, I embarked on the second part of my web development project. My goal was to enhance the security of my web application by implementing SSL certificates. Here's a detailed account of what I accomplished:

## Overview

In Day 2 of my project, I focused on enhancing the security of my web application. Specifically, I worked on the following tasks:

1. **Creating a Key Vault**: I set up an Azure key vault, a secure and centralized repository for managing keys, secrets, and certificates.

2. **Creating a Self-Signed Certificate**: Using OpenSSL in the Azure Cloud Shell, I generated a self-signed SSL certificate. This type of certificate is not signed by a trusted Certificate Authority (CA).

3. **Importing and Binding Self-Signed Certificate**: I imported the self-signed certificate into my Azure key vault and bound it to my web application. This meant encrypting the web traffic but displaying browser warnings about untrusted certificates.

4. **Creating and Binding an App Service Managed Certificate**: To address the trust issues with self-signed certificates, I created an Azure App Service Managed Certificate. This is a trusted certificate issued by a CA.


## Resources

Here are some resources that proved to be valuable during the project:

- [Azure Key Vaults](https://azure.microsoft.com/en-us/services/key-vault/#product-overview)
- [What is a self-signed certificate?](https://sectigostore.com/page/what-is-a-self-signed-certificate/)
- [Binding Certificates in Azure](https://docs.microsoft.com/en-us/azure/app-service/configure-ssl-bindings#bind-your-ssl-certificate)
- [Azure App Service Managed Certificates](https://azure.microsoft.com/en-us/updates/secure-your-custom-domains-at-no-cost-with-app-service-managed-certificates-preview/)
- [Azure App Service Documentation](https://docs.microsoft.com/en-us/azure/app-service/)
- For Microsoft Support, I referred to [How to open a support ticket](https://docs.microsoft.com/en-us/azure/azure-portal/supportability/how-to-create-azure-support-request)

## Getting Started/Prerequisites

Before I jumped into Day 2, I made sure to have the following completed from Day 1:

- Created my web application.
- Secured a unique domain name.
- Deployed a Docker container to my web application.
- Customized my web application with unique content.

## Instructions

I followed a series of step-by-step instructions to complete each part of Day 2. Below is a summary of the tasks I performed:

### Part 1: Creating a Key Vault

- Logged into the Azure portal with my personal Azure account.
- Navigated to "Key vaults" and selected "+ Create" to set up an Azure key vault.
- Configured various settings for the key vault, including subscription, resource group, name, region, and pricing tier.

### Part 2: Creating a Self-Signed Certificate

- Accessed the Azure Cloud Shell.
- Used OpenSSL to generate a self-signed certificate, specifying various parameters.
- Answered questions to define certificate details.
- Created a PFX format of the certificate for Azure.

### Part 3: Importing and Binding Self-Signed Certificate

- Uploaded the self-signed certificate to the Azure key vault.
- Opened the web application in the Azure portal.
- Configured the TLS/SSL settings.
- Imported the certificate from the key vault and bound it to the web application.

### Part 4: Creating and Binding an App Service Managed Certificate

- Returned to the web application's TLS/SSL settings.
- Created an Azure App Service Managed Certificate.
- Bound this managed certificate to the web application.

### Part 5: Answering Review Questions

- Opened the review questions document and provided answers.

## Day 2 Milestone

By the end of Day 2, I had accomplished the following:

- Created an Azure key vault for secure key, secret, and certificate management.
- Generated a self-signed SSL certificate using OpenSSL.
- Imported and bound the self-signed certificate to my web application.
- Enhanced security by creating and binding an Azure App Service Managed Certificate.
- Successfully answered review questions to evaluate my understanding.

These tasks not only secured my web application but also expanded my knowledge in systems administration, cloud security, cryptography, and networking.
