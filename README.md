# PowerAutomateManager
A xrmtoolbox plugin for managing **cloud** powerautomates.<br/>

**Featuers:**
* List **crm solution** flows
* List **My Flows** (https://flow.microsoft.com)
* List run histories
* List flow dependencies
* Export Dependencies
* Turn On/Off
* Share flows (crm users)
* Delete flows.

This tool works only with only **oauth** and **certificates** types xrmtoolbox's connection.
<br/>For how to connect and working examples please see below.<br/>
# [Go to Conections](#how-to-connect-in-xrmtoolbox-connection-types)<br/>
# [Video Help](#application-explanation)<br/>
# [Go to Application](#application-explanation)<br/>
# [Register client application](#register-client-application-1)<br/>
# [Go to Examples](#examples)<br/>


## How to Connect in xrmtoolbox (connection Types)
Once you have the xrmtoolbox you need to install this plugin form Tool Library as shown below.<br/>
![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/library.PNG)

Once the installion is done, you will see this plugin as follows:
![xrmtoolbox connections](https://raw.githubusercontent.com/yesadahmed/PowerAutomateManagerDocs/main/readme/pane.PNG)

Since this plugin connects to CE webapi so by default it requires **OAuth or Certifcate** type connections in xrmtoolbox.
<br/>For example regarding available OAuth connections in xrmtools are mentioned below:

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/raw/main/JsonToCSharp/images/Conn1.png)

Some examples are as follows.

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/sdkcontrol.png)

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/conneciont.PNG)
 AuthType=OAuth;Username=jsmith@contoso.onmicrosoft.com; Password=passcode;
Url=https://contoso:8080/Test;AppId=<GUID>;RedirectUri=app://<GUID>; LoginPrompt=Never
 
## Application Explanation
 
**Solution flows**
 ![solution flows](https://raw.githubusercontent.com/yesadahmed/PowerAutomateManagerDocs/main/readme/solutionflows.png)
 
 **My flows**
 * Create your azure client application first, [how to make client application](#register-client-application-1).
 * After creating you r application in azure, you need to click the blue link "configure your application" on plugin ![configure](https://raw.githubusercontent.com/yesadahmed/PowerAutomateManagerDocs/main/readme/setclientapp.png).
 * After successful registration you will see the login prompt will appear when you click the My flows button to get access all underneath featuers.
 * The application also cache the token once it is generated so during a session user do not need to login again and again.
 * Here it important that you must grant admin consent for the scopes you added for flow service during the client application creation in above step,
  Furhtermore to avoid errors it much better to use the same user whom you have granted admin consent.

**My flow** <br/>
![my flows](https://raw.githubusercontent.com/yesadahmed/PowerAutomateManagerDocs/main/readme/myflows.png)
 
 **Run History**
 ![flows history](https://raw.githubusercontent.com/yesadahmed/PowerAutomateManagerDocs/main/readme/history.png)
 
 **Flow dependencies**
  ![flows dependencies](https://raw.githubusercontent.com/yesadahmed/PowerAutomateManagerDocs/main/readme/dependencies.png)
  
## Register client application

[Lets go](https://htmlpreview.github.io/?https://github.com/yesadahmed/PowerAutomateManagerDocs/blob/main/readme/registerapp.html)

## Examples

   
   
   
   
   
   

  

