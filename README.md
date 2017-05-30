# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

Credentials are what what proves you have access to the information you are requesting.

> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

They are set by the server but stored on the client's web browser. The server will add the cookies in the response. you use Set-Cookie: <cookie-name>=<cookie-value> they can be a maximum of 4kb.

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

Some strength they allow for faster user authentication, The help track user information, and the keep the user form enter repetitive information. Weaknesses include, they are less secure than User auth for every site visit.

> What is the difference between a session cookie and a persistant cookie?

A session cookie expires after the end of every session. Persistent cookies will last in the browser for as long as the server has set them too.

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

Same origin policy is good because it a lot more secure when it comes to having a lot of different cookies from a lot of different places. It means that a cookie from a different host can't be messed with from a different host. This can prevent session hijaking.

> Based on what you know, how would you explain CORS?

CORS is a kind of security feature that allows the server to say what kind of resources can be accessed from different origins and share resources. Like google fonts, facebook share button, and many api's.
