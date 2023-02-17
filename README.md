# String-Function

SELECT * FROM AGENTS;
INSERT INTO AGENTS (AGENT_CODE,AGENT_NAME,WORKING_AREA) VALUES ('A110','ASHISH','GERMANY');

UPDATE AGENTS SET COUNTRY='IN'WHERE COUNTRY IS NULL OR COUNTRY='';

create table person
(Name Varchar (30),children varchar (30));

insert into person values ('Mark','Marky'),('Mark','Mark Jr'),('Mark','Jr Maria'),('john','Jhonny'),('jhon','Jane');

SELECT * FROM person;
select right('abcd',2);
select left('abcd',2);
select substring ('Ashish Rai',3%);

--length function to return the length of the string..
 select len('Ashish Rai');
  select len('Ashish Rai') as Name_Length;
  
  select subsrting('Ashish Rai',0,4);
  select substring('Ashish Rai',1,4);
  select substring('Ashish Rai',0,4);
  select substring('Ashish Rai',2,-5);
  
  SELECT SUBSTRING ('ASHISH RAI',-5,3);
  
  select* from agents;
  
  select substring (AGENT_CODE,3,3) as agent_initials from agents;
  
  Select substring (AGENT_CODE,-3,3)as agent_intitials from agents;
  Select substring (AGENT_CODE,-3,2)as agent_intitials from agents;
  Select substring (AGENT_CODE,-3)as agent_intitials from agents;
       
  Select substring (AGENT_CODE,3)as agent_intitials from agents;
  
   Select  AGENT_CODE,AGENT_NAME ,substring (AGENT_CODE,3)as agent_intitials from agents;
   
   select AGENT_CODE, AGENT_NAME, substring (AGENT_NAME,4)as agent_intitials from agents;
   
   select AGENT_CODE, AGENT_NAME, substring (AGENT_NAME,-4)as agent_intitials from agents;
   
   select AGENT_CODE, AGENT_NAME, substring (AGENT_NAME,-4,2)as agent_intitials from agents;
   
  select concat(substring('Ashish Rai',-10,1),substring('Ashish Rai',-3,1));
  
  select concat(substring('Ashish Rai',1,1),substring('Ashish Rai',8,1));
  
  select concat (PHONE_NO,COUNTRY) from agents as SLocation;
  
  select PHONE_NO ||  COUNTRY from agents as SLocation;  
 
  
  select substring('Ashish Rai',1,1)||substring('Ashish Rai',8,1));
  
