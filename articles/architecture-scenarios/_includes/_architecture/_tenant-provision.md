Everything starts with an Auth0 tenant. This is where you will be configuring your use of Auth0, and the where Auth0 assets - such as [Applications](/applications), [Connections](/connections) and [user profiles](/architecture-scenarios/implementation/${platform}/${platform}-profile-mgmt) are defined, managed and stored. Access to an Auth0 tenant is performed via the Auth0 [Dashboard](/dashboard), and via the Dashboard you can also create additional, associated tenants; you’re allowed to create more than one Auth0 tenant so that you can structure your tenants in a way that will isolate different domains of users and also support your [Software Development Life Cycle](#sdlc-support) (SDLC).

::: warning
Tenant names cannot be changed, nor reused once deleted. So, make sure you're happy with your name(s) before you create your Auth0 tenants.
:::

Determining the level of isolation you require when it comes to your user domains is an important step, and together with your branding requirements will subsequently help you determine the number of Auth0 tenants that will be required in your production environment. As we recommend you create a full suite of [SDLC supporting tenants](#sdlc-support) for every Auth0 tenant you will run in a production environment, the number of Auth0 tenants you will need to manage can quickly grow. Therefore you should consider carefully before creating multiple Auth0 tenants for production, and should consult our guidance on [Branding](/architecture-scenarios/implementation/${platform}/${platform}-branding) before making your final decision. 