Azure customers can unlock 25,000 free emails each month. These 25,000 free monthly emails will give you access to advanced reporting and analytics and [all APIs][] (Web, SMTP, Event, Parse and more). For information about additional services provided by SendGrid, see the [SendGrid Features][] page.

### To sign up for a SendGrid account

1. Log in to the [Azure Portal][].

2. In the left menu of the Azure portal, click **BROWSE ALL** and then select **Marketplace** from Browse menu.

	![command-bar-browse][command-bar-browse]

3. Click on the **Developer Services** and then search the **SendGrid** app and click it.

	![sendgrid-serach-app][sendgrid-serach-app]

4. A new blade is opened with details about the Sendgrid application, here click on **Create** button. 

    ![sendgrid-app-details][sendgrid-app-details]

5. A wizard is opened where you need to provide details about the new SendGrid account.

    ![sendgrid-create-account][sendgrid-create-account]
   
    - Enter a **name** to identify your **SendGrid** service in your Azure settings. The name must be unique in your list of subscribed Azure Store Items.

    - Select a **password** for your SendGrid account.

    - Select an existing **Resource Group** or create a new one.
 
    - Select a **subscription**.

    - Select the **SendGrid** plan you want to sign up for.

    - In **Legal Term** dialog, you can review the plan and pricing information, and the legal terms. If you agree to the terms, click Ok in that dialog.


6. After all these steps were done, click on the **Create** button and your SendGrid account will be created. A new dialog will appear from where you can manage you account.

    ![sendgrid-manage-account][sendgrid-manage-account]

    You are ready to send emails at this point.
 
    To send an email using SendGrid, you must supply your account credentials (username and password).

### To find your SendGrid credentials ###

1. Click **Settings**.

2. In the *Settings* dialog click on **Configuration**, here you find the generated **Username**, and the **Password** is the one you provided at the creation of the account.
 The Username and Password will be used later in this tutorial.

	![sendgrid-configuration][sendgrid-configuration]

	For more information on getting started with SendGrid, see [SendGrid Getting Started][].

<!--images-->

[command-bar-browse]: ./media/sendgrid-sign-up-new-portal/sendgrid_browse_all.png
[sendgrid-serach-app]: ./media/sendgrid-sign-up-new-portal/sendgrid_serach_app.png
[sendgrid-app-details]: ./media/sendgrid-sign-up-new-portal/sendgrid_app_details.png
[sendgrid-create-account]: ./media/sendgrid-sign-up-new-portal/sendgrid_create_account.png
[sendgrid-manage-account]: ./media/sendgrid-sign-up-new-portal/sendgrid_manage_account.png
[sendgrid-configuration]: ./media/sendgrid-sign-up-new-portal/sendgrid_configuration.png

<!--Links-->

[SendGrid Features]: http://sendgrid.com/features
[Azure Portal]: https://portal.azure.com
[all APIs]: https://sendgrid.com/docs/API_Reference/index.html
[SendGrid Getting Started]: https://sendgrid.com/docs


