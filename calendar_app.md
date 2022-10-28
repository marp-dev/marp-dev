# Care Community Calendars &nbsp;&nbsp;&nbsp; _2021_

![](./assets/videos/calendar-app.webm)

`HTML 5`, `CSS 3`, `Vue`, `Vuex`, `Supabase`, `PostgresSQL`, `Jamstack`

**unfortunately the app is not available publicly**

I was given the oportunity to work in this project. This is a calendar app with a PDF print using `jspdf` & data migrator/mass updater features. It was build using `Supabase` as the backend and it uses `PostgreSQL` & its `Store Fuctions`. It also has a roles features that is managed internally in the database and reflected in the rest. The UI is served through `gitlab` and it is a `JAMstack` project.

There were a couple of challenges in this project. One of them was the PDF printing itself. I was all printed manually using `jspdf` primitives. The other thing was the migrator which required some work to make all the process from the CSV, automated parsing and function calls to the REST.

The UI was build with `Vue` and there were other libraries used as `Vuex` & `ag-grid`