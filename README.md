
# ASP.NET Core

- [ASP.NET Core](#aspnet-core)
  - [What's ASP.NET Core](#whats-aspnet-core)
  - [Choose an ASP.NET Core web UI](#choose-an-aspnet-core-web-ui)
  - [Labs](#labs)
    - [Create a minimal web API with ASP.NET Core](#create-a-minimal-web-api-with-aspnet-core)

## What's ASP.NET Core

A open-source and cross-platform framework for building modern cloud based web application using .NET.

## Choose an ASP.NET Core web UI

https://docs.microsoft.com/en-us/aspnet/core/tutorials/choose-web-ui

## Labs

### Create a minimal web API with ASP.NET Core

See https://docs.microsoft.com/en-us/aspnet/core/tutorials/min-web-api

```sh

dotnet new webapi -minimal -o TodoApi

dotnet dev-certs https --trust

# -k curl 忽略ssl
curl -kv -X 'GET' 'https://localhost:7137/weatherforecast' -H 'accept: application/json'


```