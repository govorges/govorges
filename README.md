Hello! I'm `govorges`. I'm a `software developer` based in `Fort Lauderdale FL, USA.`

## ⚡ Projects of Note ⚡
- ### [OpenBroadcast](https://openbroadcast.cz/) | `WIP`
A website which allows users to upload videos and deliver them in Media RSS (MRSS) feeds. It acts as a video file host for content delivery focused on Roku/similar ITV platforms. Uses Google as an iDP and Postgres as a user data store. Still a work in progress, but ultimately it'll be a SaaS model. Mainly Python for backend operations (under Flask), vanilla JS & SCSS for the web side of things. The project's services are deployed using Docker containers (but I am inexperienced with Git Actions & proper orchestrated deployment so it's not completely automated but honestly probably shouldn't be considering it's just me on the project)

- ### [openbroadcast-bunny](https://github.com/govorges/openbroadcast-bunny) | `WIP`
A Flask API running under a Docker service which proxies requests from other internal services to Bunny's (my CDN) API. Builds WSGI application url rules using a dictionary and passes response cases into the request object. 
