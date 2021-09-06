# PowerFxCommandDesigner

Patch Command On click of Button

**Two Option Field :** 

Patch(Contacts,Self.Selected.Item,{'Enable Button':'Enable Button (Contacts)'.Yes})

Contacts --> Table Name
Self.Selected.Item --> Current Item
'Enable Button' --> Field Name
'Enable Button (Contacts)'.Yes --> Set two Option Field


**Text Field :** 

Patch(Contacts,Self.Selected.Item,{'Enable Button Text':"Success"})

Contacts --> Table Name
Self.Selected.Item --> Current Item
'Enable Button Text' --> Field Name
Success --> Set two Option Field

**Navigate:**

Navigate(Accounts)

Navigate --> Navigation
Accounts --> Table

**Navigate to Specific View**

Navigate( 'Accounts (Views)'.'My Active Accounts' )

Navigate --> Navigation
'Accounts (Views)'.'My Active Accounts' --> Table wiht View

**Create a new Record**

Patch("Task",Defaults("Task"),{Regarding:Self.Selected.Item},{Subject:"Subject of the Task"})

Task --> Entity Name
Regarding --> Field
Subject --> Field


for More Function refer to the URL
https://docs.microsoft.com/en-us/powerapps/maker/model-driven-apps/commanding-use-powerfx
