# db.ai
```
function createTable(sqlquery){

		 //Create Embedding
}

function createSqlQueryFromQuestion(question){

		 //make OPENAI call convert
}


function queryDb(sqlQuery){

		 //make Call to postgres DB with sqlQuery
}



/// WORKING



main(){


 createTable("CREATE TABLE XYZ");
 var sql = createSqlQueryFromQuestion("how many students");
 var answer = queryDb(sql);
 print answer



}
```