## Authorize.Fody

Add `[Authorize]` attribute if method has `[HttpGet]` or `[HttpPost]` and method not return `Sysstem.Net.Http.HttpResponseMessage`.

## Install

> Install-Package Authorize.Fody

## Build

> build.cmd -target build

## Publish nuget package

> build.cmd -target push