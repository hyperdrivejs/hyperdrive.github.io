---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---
**Do you get tired of building the same things over and over again?** Things like authentication, permissions, purchases, internationalization, notifications, etc. that almost every app needs?

**Do you have whiplash from how quickly the JS ecosystem evolves?** One day it seems like one set of things are popular. Come back in 6-12 months and an entirely
different set of things are vogue.

**Are you tired of having _no control_ over the architecture of your codebase?** Do the libraries we use define our architectures, or do we?

HyperdriveJS was created to solve these problems. It is not a framework. **It is a design philosophy expressed as a set of architecture-driven modules solving
common problems and patterns in web and mobile apps.**

HyperdriveJS is intentionally designed _not_ to be opinionated about what specific library you choose to use for any given pieces of functionality. It is, however, _extremely
opinionated_ about the architecture that binds those pieces together. By focusing on architecture, **HyperdriveJS creates an eye in the storm where you
and your app can rely on a stable set of canonical APIs that will change relatively slowly.**

To be more concrete, HyperdriveJS won't push any particular implementation for authentication. Do you want to use Auth0? Fine, go ahead. Do you want to use Amazon's Cognito?
Ok, that's cool, too. Do you want to use PassportJS? Fantastic.

Instead of worrying about how to implement authentication, HyperdriveJS aims to answer the question "What core API are all authentication providers trying to implement?" It
aims to provide an abstraction for authentication (and other core app services!) which your business logic can rely on without having to worry about whether or not Auth0 is going to
get too expensive in the future, or if the maintainer of that obscure authentication library you thought was cool disappears into the ether.

Because it focuses on interfaces and abstractions, **HyperdriveJS is naturally extendable.** Love HyperdriveJS's APIs and architecture, but really want to use some authentication provider it doesn't support? Write a plugin that implements Hyperdrive's API using that provider!

Does that all sound cool? HyperdriveJS and this website are still under development, but **leave us your email address if you want to hear about it when we're ready.**

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf4_oaz2JjPj5zGFGW-0nXifOq3grHGScD8GOG3qcX7LX3JAQ/viewform?embedded=true" width="640" height="451" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>