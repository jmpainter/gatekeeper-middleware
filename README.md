Gatekeeper middleware
=================

Creates a piece of authentication middleware that looks for login credentials (that is, username and password) sent over in the request headers. If valid credentials are sent, an object representing the user will be added to the request object.