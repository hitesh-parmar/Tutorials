---
parser: v2
auto_validation: true
time: 5
tags: [tutorial>beginner, topic>machine-learning, topic>artificial-intelligence, topic>cloud, software-product>sap-business-technology-platform, software-product>sap-ai-services, software-product>document-information-extraction]
primary_tag: topic>machine-learning
author_name: Juliana Morais
author_profile: https://github.com/Juliana-Morais
---

# Use Trial to Set Up Account for Document Information Extraction and Get Service Key
<!-- description --> Get access to the service Swagger UI using a booster in SAP Business Technology Platform (SAP BTP) Trial that automatically creates a service instance, and the associated service key for Document Information Extraction.

## Prerequisites
- You have created a trial account on SAP BTP: [Get a Free Account on SAP BTP Trial](hcp-create-trial-account)
- You have a trial subaccount and dev space with **US East (VA) - AWS** as region: [Manage Entitlements on SAP BTP Trial](cp-trial-entitlements). See also [Create a Subaccount](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/261ba9ca868f469baf64c22257324a75.html).

## You will learn
  - How to access your trial account
  - What are interactive guided boosters
  - How to use the **Set up account for Document Information Extraction** booster to assign entitlements, update your subaccount, create a service instance and the associated service key for Document Information Extraction.

---

### Go To Your Trial Account


1. In your web browser, open the [SAP BTP Trial cockpit](https://cockpit.hanatrial.ondemand.com/).

2. Navigate to the trial global account by clicking **Go To Your Trial Account**.

    <!-- border -->![Trial global account](01_Foundation20Onboarding_Home.png)

    >If this is your first time accessing your trial account, you'll have to configure your account by choosing a region. Please select **US East (VA) - AWS**. Your user profile will be set up for you automatically.

    >Wait till your account is set up and ready to go. Your global account, your subaccount, your organization, and your space are launched. This may take a couple of minutes.

    >Choose **Continue**.

    ><!-- border -->![Account setup](02_Foundation20Onboarding_Processing.png)

    >For more details on how to configure entitlements, quotas, subaccounts and service plans on SAP BTP Trial, see [Manage Entitlements on SAP BTP Trial](cp-trial-entitlements).



### Run booster


SAP BTP creates interactive guided boosters to automate cockpit steps, so users can save time when trying out the services.

Now, you will use the **Set up account for Document Information Extraction** booster to automatically assign entitlements, update your subaccount, create a service instance and the associated service key for Document Information Extraction.

1. On the navigation side bar, click **Boosters**.

    <!-- border -->![Service Key](access-booster.png)

2. Search for **Set up account for Document Information Extraction** and click the tile to access the booster.

    <!-- border -->![Service Key](access-booster-tile.png)

3. Click **Start**.

    <!-- border -->![Service Key](booster-start.png)

    >If you have more than one subaccount, the booster will choose automatically the correct subaccount and space, but this will require that you click **Next** twice and **Finish** once, before being able to see the **Success** dialog box.

    <!-- border -->![Service Key](booster-success.png)



### Get service key


You have successfully used the booster **Set up account for Document Information Extraction** to create a service key for Document Information Extraction.

Click **Download Service Key** to save the service key locally on your computer.

<!-- border -->![Service Key](booster-success-key.png)

>If you face any issue with the booster **Set up account for Document Information Extraction**, you can alternatively follow the steps in [Create Service Instance for Document Information Extraction](cp-aibus-dox-service-instance) to create a service key for Document Information Extraction manually.

You are now all set to [Get OAuth Access Token for Document Information Extraction Using Any Web Browser](cp-aibus-dox-web-oauth-token). Step 4 is optional. If you're not interested, you can set it to **Done** and go directly to the next tutorial.




### Access service instance and service key (optional)


> This is an optional step. Use it only if you want to access the service instance and service key, you created with the **Set up account for Document Information Extraction** booster, without having to run it once again.

Do the following to access your service instance and service key, without having to run the **Set up account for Document Information Extraction** booster once again:

1. Close the booster **Success** dialog box.

    <!-- border -->![Service Key](leave-success.png)

2. Access your trial account.

    <!-- border -->![Service Key](trial-account.png)

3. Click **Account Explorer** on the navigation side bar and select **trial** to access your subaccount.

    <!-- border -->![Service Key](subaccount.png)

4. Click **Instances and Subscriptions** on the navigation side bar. You see the service instance you created with the **Set up account for Document Information Extraction** booster.

    <!-- border -->![Service Key](service-instance.png)

5. Click the navigation arrow to open the details of your service instance. Then, click the dots to **View**, **Download** or **Delete** your service key.

    <!-- border -->![Service Key](service-key.png)

Congratulations, you have completed this tutorial.

