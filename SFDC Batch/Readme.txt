
        /*how to call the batch in AW
    String e = 'Account'; // Object to be updated
    String f = Enterprise_Account_Status_c'; // field to be updated.
    String v = 'Bronze'; // value with which field will be populated.
    String q = 'SELECT ' + f + ' FROM ' + e +' where where recordtype.name ='Customer';  // Query to fetch the customer account record type';
    Id batchInstanceId1 = Database.executeBatch(new GenericBatchClass(q,e,f,v));
*/

We can replace the field and value as per the requirement.