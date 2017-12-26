# ovirt_auth_prototype

1. Start the app `> python app.py`.
2. By Default the app starts on `localhost` @ port `5000`
3. The 2 endpoints app starts are `/list_vm` and `/list_host`
4. In initial request where no session is created you need to pass Ovirt `Username and Password` in request header 
    as `user & password` for authentication.
5. The follow on request can be send without username and password until session is not expired.
