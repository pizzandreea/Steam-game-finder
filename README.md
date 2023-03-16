# Steam-game-finder
The process extracts Steam games based on a keyword and filters like Operating System, Lowest Price etc and emails them to the person that requested them. Using an excel with names, game type and preferences the process opens Steam, logs in and searches specific games based on the keywords and filters to suit the requested games. After all the scraping is completed and data is collected in an excel, it is sent via email to the person that requested the specific games.
### Schimbati path-uri:

![image](https://user-images.githubusercontent.com/72975663/212358112-28a9fb28-c9e7-4172-a406-fcf4d93a735a.png)
![image](https://user-images.githubusercontent.com/72975663/212358252-26a9f080-23f7-4832-9c2d-c454ba8c4850.png)

cred mai e un path dar nu stiu unde..

Daca vreti sa mearga, intrati [aici](https://cloud.uipath.com/portal_/register), si faceti setup la Orchestrator cu urmatoarele asset-uri de tip credential:
- Steam
  - username: andreeaRPA
  - password: parola12345#
- Google
  - email: steamgames.finder@gmail.com
  - password: parola12345#
  
apoi schimbati aici<br/>
![image](https://user-images.githubusercontent.com/72975663/212359395-7b41c329-0cc0-4465-a5f6-f98d8c8b80b5.png)
si aici<br/>
![image](https://user-images.githubusercontent.com/72975663/212359492-7bbff967-3db9-49d5-b6fc-b1a9562769fe.png)
ca sa folositi asset-urile voastre.
