**What is IdentityServer4?**
IdentityServer4 is an OpenID Connect and OAuth 2.0 Framework for ASP.NET Core.

**OpenID Connect:** 
Third generation of Open ID after Open ID 2.0, is primarily based on OAuth 2.0 authentication. It allows computing clients to verify the identity of an end-user and to obtain the basic profile information about the end-user in an interoperable and REST-like manner. The specification is extensible, allows participants to use optional features such as encryption of identity data, discovery of OpenID Providers, and session management etc.

OpenID Connect performs many of the same tasks as OpenID 2.0, but in an API-friendly way, and usable by native and mobile applications.

**OAuth 2.0 Terminology:**
1) Client: it’s the software like web-browser, mobile app and any code that requests a resource.
2) Resources: what you want to protect using identityserver4
3) Access Token: it is the token that is used by a client to access the API resource.
4) Refresh Token: each access token has an expiry date. The refresh token is used to get a new access token without the user interaction.
5) Grant Type: it is the type of interaction between the client and the IdentityServer. based on your client you should choose the suitable grant type.

**Why to choose Identity Server 4:**

Authentication as a Service: Centralized login logic and workflow for all of your applications (web, native, mobile, services).
Single Sign-on / Sign-out: Single sign-on (and out) over multiple application types.
Access Control for APIs: Issue access tokens for APIs for various types of clients.
Federation Gateway: Support for external identity providers like Azure Active Directory, Google, Facebook etc. This shields your applications from the details of how to connect to these external providers.
Focus on Customization: Many aspects of IdentityServer can be customized to fit your needs. Since IdentityServer is a framework and not a boxed product or a SaaS, you can write code to adapt the system the way it makes sense for your scenarios.
Mature Open Source: IdentityServer uses the permissive Apache 2 license that allows building commercial products on top of it. It is also part of the .NET Foundation which provides governance and legal backing.
Free and Commercial Support

**Important Component of Identity Server4 Application:-**

1) Discovery document: Useful for clients while using IdentityServer4 applications as their provider. List of all endpoints like authorization endpoints, token endpoints etc.
Supported scops, claims, grant types, response types, response modes, auth methods, token signing algorithms etc.
