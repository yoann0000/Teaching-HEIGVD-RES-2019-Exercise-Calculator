1. What transport protocol do we use?
client-server protocol - TCP

2. How does the client find the server (addresses and ports)?
80

3. Who speaks first?
after the connection is set up, the server asks for input.

4. What is the sequence of messages exchanged by the client and the server?
enter first number - client replies - enter second number - client replies - enter operator - client replies - server returns result

5. What happens when a message is received from the other party?
check if valid reply from client
if not ask again
client replies if one is expected
server only makes demands

6. What is the syntax of the messages? How we generate and parse them?
numbers are reals parsed as strings
operators are strings (add, sub, mult, div)

7. Who closes the connection and when?
The user whenever he is done (i.e. user got result)
