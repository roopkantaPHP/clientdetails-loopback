# clientdetails-loopback
Rest API to do CRUD operation using Loopback

**Prerequisite**

- Ubuntu or any linux system
- Node v10.19.0 installed
- Mongodb v4.4.1
- Clone Repo in project folder

**Database setup**
 - Run Mongo server
 - Create DB name "clientinfo"
 - Create Collection name "clientinfo"

**Instruction for LoopBack**

- run sudo npm install -g loopback – cli  to install loopback
- Navigate to the folder where package.json is available
- Run npm install
- Run node .
- 2 URLs get generated
    1. http://localhost:3000
    2. http://localhost:3000/explorer
    
- Run http://localhost:3000/explorer in browser for Loopback GUI

**Rest APIs**
APIs can be exposed on http://<HOST>:<PORT>/api
  
- Creat client:/clientinfos ((HTTP Method: POST))
- Get All Client: /clientinfos (HTTP Method: GET)
- Get client by id: /clientinfos/{id}(HTTP Method: GET)
- Update existing client info: /clientinfos/{id}(HTTP Method: PUT)
- Delete existing client : /clientinfos/{id} (HTTP Method: DELETE)



