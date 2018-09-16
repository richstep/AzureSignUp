# Prove Domain Ownership

## Prerequisites: 
- Access to the domain registrar.
    - Someone at your business registered your company's domain name (for example, 11gwireless.com). You'll need to find them and ask them to perform step #3 below.

## Steps

1.	Open a new browser tab and navigate to https://portal.azure.com. Sign-in using your work or school account. You may have created this account while following [these](README.md) instructions.

2.	On the left menu, click  AZURE ACTIVE DIRECTORY and then click on CUSTOM DOMAIN NAMES.

    ![](images/proveDomain.jpg)

3.	Follow the instructions to create a new TXT record with your domain name registrar.
-   Note that adding a TXT record doesn't change any behaviors such as mail routing or web hosting.
-   If verification fails, wait an hour. DNS records must propagate before Azure can verify the domain.
-   You can check the progagation of the newly created TXT record [here](https://www.whatsmydns.net/#TXT/google.com).

4.	You are done!!
