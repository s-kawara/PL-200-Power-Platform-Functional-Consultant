---
lab:
    title: 'Lab: Validate lab environment'
    module: 'Module 0: Course introduction'
---

Module 1: Introduction to the Power Platform 
=================================

## Practice Lab – Validate lab environment

### Important Notice (Effective November 2020):
Common Data Service has been renamed to Microsoft Dataverse. Some terminology in Microsoft Dataverse has been updated. For example, entity is now table and field is now column. 

While the application is in the process of updating its user experience, some references to terminology like the Common Data Service (now **Dataverse**), entity (now **table**), field (now **column**), and record (now **row**) may be out of date. Please keep this in mind as you work through the labs. We expect to have our content fully up to date very soon. 

For more information and for a complete list of affected terms, please visit [What is Microsoft Dataverse?](https://docs.microsoft.com/en-us/powerapps/maker/common-data-service/data-platform-intro#terminology-updates)


Scenario
--------

In this Module 0 lab, you will acquire a Power Platform trial tenant and access the Power Platform admin center. In the admin center, we will create an individual environment for configuration during the course.

Exercise 1 – Acquire your Power Platform trial tenant 
------------------------------------------

1. Copy your **Microsoft 365 credentials** from the Authorized Lab Hoster.

2. Navigate to <https://powerapps.microsoft.com/>. Click **Try free.**

3. Under **Get started**, enter the email address from your Microsoft 365 credentials in the text box that says **Enter your work email address.** Click **Submit**

4. You will see a prompt that you have an existing account with Microsoft. Select **Sign in.**

5. Enter the password provided by the Authorized Lab Hoster. Click **Sign in.** 

6. At the **Almost there** prompt, click **Get Start.**

	**Note:** Depending on your internet browser, you may be prompted to sign in again. Select **Sign in**, click the email account you just signed in with, and continue.

6. Select **Yes** to stay signed in.


Exercise 2 - Create your environment 
------------------------------------------

In this exercise, you will be create your **Practice** environment that you will do the majority of your lab work in.

### Task 1 – Create environment

1.  Access <https://admin.Powerplatform.com> and log in with your Microsoft 365 credentials if prompted again.

2. If you are not automatically directed there, select **Environments** and click **+New.**

    - For **Name**, enter **[my initials] Practice.** (Example: AJ Practice.)
    
    - For **Type**, select **Trial.** You may see an option for **Trial (subscription-based)** - select the option that only says **Trial.**
    
    - Change the **Create a database for this environment?** toggle to **Yes.**
    
    - Leave all other selections as default and click **Next.**
    
    - On the next tab, change the toggle for **Deploy sample apps and data?** to **Yes.** Click **Save**.

3. Your **Practice** environment should now show in the list of Environments. 

4. Your environment may take a few minutes to provision. Refresh the page if needed. When your environment is prepared, select your **Practice** environment by clicking on the ellipses next to its name to expand the drop down menu and select **Settings.** 

3.  Explore the different areas in **Settings** that you are interested in but do not make any changes yet. 
