# Acac Parameters


  You are using standard parameter (EXAMPLE) that's why u are getting the above error. For resolving this error you need to create own parameter. After that Assign Parameters to Accrual Object Categories. For creating your own parameter follow the below standard srocess:

  Before assigning a user-defined parameter to an accrual object category, you must add the parameter as a field to the SAP structure ACAC_PARAMETERS. To do so, proceed as follows:

  1. From the SAP Easy Access screen, choose
Tools -> ABAP Workbench -> Development -> ABAP Dictionary (transaction SE11).2. In the database table field, enter ACAC_PARAMETERS and choose Change.3. Choose Edit -> Include -> Insert4. In the Structure field, enter CI_ACAC_PARAMETERS and choose Continue.5. Enter the required user-defined field.6. Choose Activate.7. Save your settings.
