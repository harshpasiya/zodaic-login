# zodaic-login

Login forwarder for Zodaic Market Terminal's Angel One SmartAPI connection.

Angel One only accepts a public redirect URL, so its login lands on this GitHub Pages page,
which immediately forwards it to the app running on your own computer
(`http://127.0.0.1:5000/angel/callback`). The page loads no other resources, sends nothing
anywhere except your own computer, and stores nothing.

Redirect URL to register at smartapi.angelone.in → My Apps:
`https://harshpasiya.github.io/zodaic-login/`
