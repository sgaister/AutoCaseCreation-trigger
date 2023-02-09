# AutoCaseCreation-trigger

This Apex trigger automatically creates a Case record when an Opportunity is closed as lost and its probability of closing is less than 50%. The case subject and description are constructed based on the Opportunity name and the related Account name.

This can be useful for your sales team to follow up on lost opportunities and improve their win rate.

-----

Before using this trigger you need to create custom field OpportunityId:
1. From the Object Manager Object Manager page, select an object Case.
4. From the sidebar, click Fields & Relationships.
5. Click New to create a custom field.
6. Choose a data type as Text. Click Next.
7. Field Label: OpportunityId
   Length: 20
   Field Name: OpportunityId
8. Select the field’s visibility and edit access.
9. Click Next. Then click Save
