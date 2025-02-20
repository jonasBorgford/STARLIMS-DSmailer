These scripts are used to email the output of a datasource in STARLIMS.

Utilities.SendQueryResultsAsEmail runs the DS then calls scripts to convert the return to HTML table. Finally, it calls Utilities.GenericSendHTMLEmail to send the return.

Utilities.DSToArrayWithHeaders converts a DS object to a 2D array (including the headers or column names in the first row of the array).

Utilities.2DArrayToHTMLTable converts a 2D array into a HTML table.

Utilities.GenericSendHTMLEmail builds the email and submits to the outbox.

Works in STARLIMS v11.
