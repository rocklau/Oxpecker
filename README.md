# Oxpecker

![Oxpecker](https://github.com/Lanayx/Oxpecker/raw/develop/images/oxpecker.png)

* [Oxpecker Nuget package](https://www.nuget.org/packages/Oxpecker)
* [Oxpecker.ViewEngine Nuget package](https://www.nuget.org/packages/Oxpecker.ViewEngine)
* [Oxpecker.Htmx Nuget package](https://www.nuget.org/packages/Oxpecker.Htmx)
* [Oxpecker.OpenApi Nuget package](https://www.nuget.org/packages/Oxpecker.OpenApi)

Oxpecker is a functional wrapper around ASP.NET Core Endpoint routing. Repository contains both main project and other related packages.

This library is basically a revised version of [Giraffe](https://github.com/giraffe-fsharp/Giraffe), it mostly sticks to Giraffe's successful API (hence the name). Improvements involve changing some core types, performance of template handlers, simplifying handlers and dropping a lot of outdated functionality.

Medium introductory post: https://medium.com/@lanayx/the-oxpecker-ef9df3dfb918

Oxpecker project is planned to be moved to `fsprojects` organization once it reaches 200 stars

## Features:

- Native [ASP.NET Core Endpoint routing](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/routing) integration
- ViewEngine with convenient DSL for HTML
- Strongly typed route parameters
- Endpoint handlers and endpoint middlewares, flexible composition
- JSON binding and serialization
- Form binding
- URL parameters binding
- Response caching
- Streaming
- Authorization
- eTag support
- IResult support
- Many useful **HttpContext** extensions

## Examples:
- [Empty template](https://github.com/Lanayx/Oxpecker/blob/develop/examples/Empty)
- [Dump of different features all in one place](https://github.com/Lanayx/Oxpecker/blob/develop/examples/Basic)
- [Full CRUD example with functional DI](https://github.com/Lanayx/Oxpecker/blob/develop/examples/CRUD)
- [HTMX sample application](https://github.com/Lanayx/Oxpecker/tree/develop/examples/ContactApp)
- [Oxpecker version of the traditional ASP.NET WeatherApp](https://github.com/Lanayx/Oxpecker/tree/develop/examples/WeatherApp)

## Documentation links:

* [Oxpecker Readme](https://github.com/Lanayx/Oxpecker/blob/develop/src/Oxpecker/README.md)
* [Oxpecker.ViewEngine Readme](https://github.com/Lanayx/Oxpecker/blob/develop/src/Oxpecker.ViewEngine/README.md)
* [Oxpecker.Htmx Readme](https://github.com/Lanayx/Oxpecker/blob/develop/src/Oxpecker.Htmx/README.md)
* [Oxpecker.OpenApi Readme](https://github.com/Lanayx/Oxpecker/blob/develop/src/Oxpecker.OpenApi/README.md)
* [Migration from Giraffe](https://github.com/Lanayx/Oxpecker/blob/develop/MigrateFromGiraffe.md)

## develop vs main branch:

**develop** is a development branch, projects are linked with each other using project references. Use this branch to send PRs.

**main** is a production branch, projects are linked with each other using nuget packages. Packages are published from this branch.
