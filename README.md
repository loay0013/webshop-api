Webshop API er en backend-applikation udviklet med Node.js og Express, designet til at håndtere e-handelsfunktionalitet såsom produktstyring, brugerautentifikation og ordrebehandling. Dette API fungerer som serverkomponenten for en webshop og leverer nødvendige endpoints til frontend-applikationer.

🚀 Funktioner
CRUD-operationer for produkter
Brugerregistrering og -login med JWT-autentifikation
Ordreoprettelse og -styring
Datavalidering med [Joi eller et andet bibliotek]
[Andre vigtige funktioner]
📦 Teknologier anvendt
Node.js – JavaScript-runtime til server-side applikationer
Express – Webapplikationsframework for Node.js
MongoDB – NoSQL-database til datalagring
Mongoose – ODM-bibliotek til MongoDB og Node.js
JSON Web Tokens (JWT) – Til sikker brugerautentifikation


🔧 Installation
Følg disse trin for at installere og køre projektet lokalt:

1.Klon repoet
git clone https://github.com/loay0013/webshop-api.git
cd webshop-api
2.Installer afhængigheder
npm install
3.Konfigurer miljøvariabler Opret en .env-fil i projektets rodmappe og tilføj følgende variabler:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
4.Start serveren
npm start
Serveren vil køre på http://localhost:5000.
