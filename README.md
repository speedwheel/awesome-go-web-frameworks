# Awesome Web Frameworks for Gophers

You may not need a web framework if you design a small application for yourself, but if you're going production then you definitely will need one, a good one.

And while you think that you have the necessary knowedge and experience, would you risk to code all of those features by yourself?
Do you have the time to find a production-class external package to do the job? Are you sure that this will be aligned with the rest of your app?

These are the serious reasons that drive even the best of us to use frameworks, we don't want to code all those necessary features by ourselves if someone else already did the hard work.

## Table of Contents

- [Introduction](#introduction)
- [About Popularity](#popularity)
- [About Learning Curve](#learning-curve)
- [About Core Features](#core-features)
- [Used Vocabular](#vocabulary)
- [Contributing](#contributing)

## Introduction

[Go](https://golang.org) is a rapidly growing open source programming language designed for building simple, fast, and reliable software. Take a look [here](https://github.com/golang/go/wiki/GoUsers) to see which great companies use Go to power their services.

This repository has all the necessary information to help developers learn more about the best options that are out there to develop web applications with Go.

The repository contains the most detailed framework comparison that is out there, by comparing the the most known web frameworks from as many angles as possible: popularity, support and built'n features:

**Beego**: _An open-source, high-performance web framework for the Go programming language._
* https://github.com/astaxie/beego
* https://beego.me

**Buffalo**: _Rapid Web Development w/ Go._
* https://github.com/gobuffalo/buffalo
* https://gobuffalo.io

**Echo**: _A high performance, minimalist Go web framework._
* https://github.com/labstack/echo
* https://echo.labstack.com

**Gin**: _HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance._
* https://github.com/gin-gonic/gin
* https://gin-gonic.github.io/gin

**Iris**: _The fastest web framework for Go in (THIS) Earth. HTTP/2 Ready to GO. MVC when you need it._
* https://github.com/kataras/iris
* https://iris-go.com

**Revel**: _A high productivity, full-stack web framework for the Go language._
* https://github.com/revel/revel
* https://revel.github.io

## Popularity

> Sorted by the popularity (stars)

| Name | Stars | Forks | Issues Open | Issues Closed  | Birth Year | Latest Update | Author |
|---|---|---|---|---|----|----|----|
| Beego | 12,908 | 2,923 | 362 | 1,593 | 2012  | 2017-11-13 | [@astaxie](https://github.com/astaxie) |
| Gin | 12,875 | 1,503 | 113 |  601 |  2014 | 2017-11-13 | [@manucorporat](https://github.com/manucorporat) |
| Revel | 9,059 | 1,185 | 39 |  721 | 2011 | 2017-11-06 | [@robfig](https://github.com/robfig) |
| Echo | 8,655 | 750 | 72 |  611 |  2015 | 2017-11-12 | [@vishr](https://github.com/vishr) |
| Iris | 8,134 | 853 | 2 |  695 | 2016 | 2017-11-10 | [@kataras](https://github.com/kataras) |
| Buffalo | 1,835 | 134 | 29 |  321 |  2014 | 2017-11-13 | [@markbates](https://github.com/markbates) |

## Learning Curve

Name | Examples | Reference | Real time support |
|---|:---:|---|---|
| Iris | 92 | https://github.com/kataras/iris/tree/master/_examples | [rocket chat](https://chat.iris-go.com) |
| Buffalo | 6 | https://gobuffalo.io/docs/installation | [slack](https://gophers.slack.com/messages/buffalo/) |
| Beego | 49 | https://beego.me/docs | |
| Echo | 20 | https://echo.labstack.com/cookbook/hello-world | |
| Gin | 15 | https://github.com/gin-gonic/gin/tree/master/examples | [gitter](https://gitter.im/gin-gonic/gin) |
| Revel | 6 | http://revel.github.io/examples/index.html | [gitter](https://gitter.im/revel/community) |

Great job by astaxie and kataras here, hopfully and the other frameworks will catch up with more examples, at least for me, if I switch to a new framework, that's the most resourceful place to quickly grasp as much information as possible. An example it's like 1000 words.

## Core Features

> Sorted by the most to less featured

| Name |Iris|Beego|Revel|Echo|Gin|Buffalo|
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| Router: Named Path Parameters & Wildcard[*](#router-named-path-parameters--wildcard) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">- |
| Router: Regex[*](#router-regex) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png">  | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">- |
| Router: Grouping[*](#router-grouping) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | ❔ | ❔ | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">- |
| Router: All the above Mixed Without Conflict[*](#all-the-above-mixed-without-conflict) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Router: Custom HTTP Errors[*](#router-custom-http-errors) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |
| 100% compatible with net/http[*](#100-compatible-with-nethttp) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png">  |  ❔ | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">  | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |
| Middleware ecosystem[*](#middleware-ecosystem) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Sinatra-like API[*](#sinatra-like-api) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Server: Automatic HTTPS[*](#server-automatic-https) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | ❔| <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Server: Gracefully Shutdown[*](#server-gracefully-shutdown) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Server: Multi Listeners[*](#server-multi-listeners) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Full HTTP/2[*](#full-http2) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | ❔| ❔ | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | standard | standard |
| Subdomains[*](#subdomains) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | secondary | secondary |  secondary |  secondary | secondary |
| Sessions[*](#sessions) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | secondary |
| Websockets[*](#websockets) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| View (aka Templates) Embedded Into App[*](#view-aka-templates-embedded-into-app) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| View Engine: STD[*](#view-engine-std) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| View Engine: Pug[*](#view-engine-pug) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| View Engine: Django[*](#view-engine-django) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| View Engine: Handlebars[*](#view-engine-handlebars) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| View Engine: Amber[*](#view-engine-amber) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Renderer: Markdown, JSON, JSONP, XML...[*](#renderer-markdown-json-jsonp-xml) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| MVC[*](#mvc) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">- | generator | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Caching[*](#catching) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">| <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| File Server[*](#file-server) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> |
| File Server: Embedded Into App[*](#file-server-embedded-into-app) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Response can be Modified Many times through lifecycle before sent[*](#response-can-be-modified-many-times-through-lifecycle-before-sent) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |  <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Gzip[*](#gzip) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | middleware | middleware | middleware |
| Testing Framework[*](#testing-framework) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Typescript Transpiler[*](#typescript-transpiler) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Online Editor[*](#online-editor) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Logging System[*](#logging-system) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">- | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png">- | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Maintenance & Auto-Updates[*](#maintenance--auto-updates) | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2714.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> | <img height="15" width="15" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2796.png"> |
| Performance | ★★★★★ | ★★★ | ★★ | ★★★★★ | ★★★★★ | ★★★ |

```
The most known "Web frameworks" in Go are not really frameworks, meaning that:
Echo, Gin and Buffalo are not really (fully featured) web frameworks
but the majority of Go community thinks that they are.
Therefore they think that they are comparable with Iris, Beego or Revel,
because of that we have the obligation to include them into this list as well.

All of the above frameworks, except Beego and Revel, can adapt any middleware
that was created for net/http, some of those can do this with ease and others
with some hacking [even the pain is a choice here].
```
## Vocabulary

### Router: Named Path Parameters & Wildcard

When you can register a handler to a route with dynamic path.

Example Named Path Parameter:
```
"/user/{username}" matches to "/user/me", "/user/speedwheel" etc
```

The `username` path parameter's value is the `"/me"` and `"speedwheel"` respectfully.

Example Wildcard:
```
"/user/{path *wildcard}" matches to
"/user/some/path/here",
"/user/this/is/a/dynamic/multi/level/path" etc
```
The `path` path parameter's value is the `"some/path/here"` and `"this/is/a/dynamic/multi/level/path"` respectfully.

> Iris supports a feature called `macros` as well, can be described as `/user/{username:string}` or `/user/{username:int min(1)}`.

### Router: Regex

When you can register a handler to a route with dynamic path
with filters some that should be passed in order to execute the handler.

Example:
```
"/user/{id ^[0-9]$}" matches to "/user/42" but not to "/user/somestring"
```

The `id` path parametert's value is `42`.

### Router: Grouping

When you can register common logic or middleware/handlers to a specific group of routes that share the same path prefix.

Example:
```
myGroup := Group("/user", userAuthenticationMiddleware)
myGroup.Handle("GET", "/", userHandler)
myGroup.Handle("GET", "/profile", userProfileHandler)
myGroup.Handle("GET", "/signup", getUserSignupForm)
```

- /user
- /user/profile
- /user/signup

You can even create subgroups from a group:
```
myGroup.Group("/messages", optionalUserMessagesMiddleware)
myGroup.Handle("GET', "/{id}", getMessageByID)
```
- /user/messages/{id}

### Router: All the above Mixed Without Conflict

This is an advanced, but useful feature that many of us hope that is supported by a router or a web framework, currently only Iris supports this in the Go world.

It means that something like `/{path *wildcard}` and `/user/{username}` and `/user/static` and `/user/{path *wildcard}` can be registered in the same router which can correctly matches without conflict by static paths (`/user/static`) or wildcard (`/{path *wildcard}`).

### Router: Custom HTTP Errors

When you can reigster a handler for an "error" status code. An error http status code is a `>=400` status code, i.e `NotFound 404`.

Example:
```
OnErrorCode(404, myNotFoundHandler)
```

Most of the web frameworks above support only `404`, `405` and `500` registration, but fully featured like `Iris, Beego and Revel` supports any status code or even `any error` code ( `any error` is supported by Iris only).

### 100% compatible with net/http

Means that you have:
- the framework gives you a context with direct access to the `*http.Request` and `http.ResponseWriter`.
- a way to convert an `net/http` handler to a specific framework's type of Handler.

### Middleware ecosystem

When you don't have to wrap each handlers with middleware by your own, but the framework gives you a full engine to define the flow, globally or per route or per group of routes, i.e `Use(middleware)`, `Done(middleware`) etc. 

### Sinatra-like API

Register in runtime handlers to routes for specific HTTP Methods (and path parameters).

Example:
```
.Get or GET("/path", gethandler)
.Post or POST("/path", postHandler)
.Put or PUT("/path", putHandler) and etc.
```

### Server: Automatic HTTPS

When the framework's server supports registering and auto-renewing the SSL certifications to manage the SSL/TLS incoming connections (https). The most famous automatic https provider is the [letsencrypt](https://letsencrypt.org/). 

### Server: Gracefully Shutdown

When pressing `CTRL + C` to close your terminal application; the server will close itself gracefully, waiting for some connections to finish their job (with a specicified timeout) or fire a custom event to do cleanup (i.e database Close).

### Server: Multi Listeners

When tje framework's server supports registering custom `net.Listener` or serve a web applications using more than one http server and address.

### Full HTTP/2

When the framework supports HTTP/2 with https and the server `Push` feature with ease.

### Subdomains

When you can register routes per x,y subdomains directly from your web application.

`secondary` menas that this is not supported by the framework as a feature but you can still do it by starting multiple http servers, the downsides of this is that the main app and subdomain are not connected and is impossible to share logic between them by default.

### Sessions

When http sessions are supported and ready to use inside your specific handler(s).

- Some of the web frameworks supports back-end database to store the sessions so you can get persistence between server restarts.
- Buffalo uses the gorilla sessions, which are little bit slower than the rest of the implementations.

Example:
```
func setValue(context http_context){
    s := Sessions.New(http_context)
    s.Set("key", "my value")
}

func getValue(context http_context){
    s := Sessions.New(http_context)
    myValue := s.Get("key")
}

func logoutHandler(context http_context){
    Sessions.Destroy(http_context)
}
```

Wiki: https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#HTTP_session

### Websockets

When the framework supports websocket communications protocol. The implementations are different. 

You should search their examples to see what suits you. My co-worker who tried all of those told me that Iris  implements the most featured webosocket connections with the easier API compared to the rest.

Wiki: https://en.wikipedia.org/wiki/WebSocket


### View (aka Templates) Embedded Into App

Normally you have to transfer all of your template files side by side with your web application's executable file. Embedded Into App means that the framework supports integration with [go-bindata](https://github.com/jteeuwen/go-bindata) so the final executable file contains the templates inside it, represented as `[]byte`.

#### What is a view engine

When the framework supports template loading, custom and built'n template functions to save our lives on critical parts. 

### View Engine: STD

When framework supports loading templates via the standard `html/template` parser.

### View Engine: Pug

When framework supports loading templates via a `Pug` parser.

### View Engine: Django

When framework supports loading templates via a `Django` parser.

### View Engine: Handlebars

When framework supports loading templates via a `Handlebars` parser.

### View Engine: Amber

When framework supports loading templates via an `Amber` parser.

### Renderer: Markdown, JSON, JSONP, XML...

When the framework's context gives you an easy way to send/and customize a response of various content types of with ease.

### MVC

Model–view–controller (MVC) is a software architectural pattern for implementing user interfaces on computers. It divides a given application into three interconnected parts. This is done to separate internal representations of information from the ways information is presented to, and accepted from, the user. The MVC design pattern decouples these major components allowing for efficient code reuse and parallel development.

- Iris supports the full MVC features, can be registered at runtime.
- Beego supports only method and models matching, can be registered at runtime.
- Revel supports methods, path and models matching, can be registered only via a generator (a different software that you have to run to build your web application).

Wiki: https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller

### Caching

A web cache (or HTTP cache) is an information technology for the temporary storage (caching) of web documents, such as HTML pages and images, to reduce server lag. A web cache system documents passing through it; subsequent requests may be satisfied from if certain conditions are met.[1] A web cache system can refer either to an appliance, or to a computer program.

Wiki: https://en.wikipedia.org/wiki/Web_cache

### File Server

When you can register a (physical) directory to a route which will serve the files of this directory to the client automatically.

### File Server: Embedded Into App

Normally you have to transfer all static files (like assets; css, javascript files...) along with the application's executable file. Frameworks that support this feature gives you the chance to embed all those data inside your application, represented as `[]byte`, their response time is also faster because server can serve them directly without looking up for the file in a physical location.

### Response can be Modified Many times through lifecycle before sent

Currently only Iris supports this via built'n response writer in its http_context.

When framework supports this you can retrieve or reset or modify the written status code, body and headers before sent to the client (in net/http based web frameworks this is not possible by default because the body and status code cannot be retrieved or changed when written).

### Gzip

When you're inside a route's handler and you can change the response writer in order to send a response using the gzip compression, the framework should take care of the sent headers, it should reset the response write back to normal if any error occurs and also it should be able to check if gzip is supported by client.

> gzip is a file format and a software application used for file compression and decompression

Wiki: https://en.wikipedia.org/wiki/Gzip

### Testing Framework

When you can test your HTTP using a specific framework library, that its work is to help you write better tests with ease.

Example (currently, only Iris supports that)
```
func TestAPI(t *testing.T) {
    app := myIrisApp() 
    tt := httptest.New(t, app)
    tt.GET("/admin").WithBasicAuth("name", "pass").Expect().
    Status(httptest.StatusOK).Body().Equal("welcome")
}
```
`myIrisApp` returns your imaginary web application,
it has got a GET handler for `/admin` which is protected by basic authentication.

The above simple test checks if `/admin` responded with `Status OK` and authentication passed with specific username and password and its body is `"welcome"`.

### Typescript Transpiler

Typescript goal is to be a superset of ES6 that, in addition to all the new stuff that the standard is defining, will add a static type system. Typescript has also a transpiler that converts our Typescript code (i.e. ES6 + types) to ES5 or ES3 javascript code so we can use it in today browsers.

### Online Editor

With the help of the online editor you can Quickly and Easy compile and run go code online.

### Logging System

Custom logging System thaty extend the native log package behavior by providing useful features like color coding, formatting, log levels separation, different logging backends, etc.

### Maintenance & Auto-Updates

Inform users of your framework of "on the fly "updates in a non-intrusive way.

# Contributing

- Fork the project.
- Make your changes.
- Make a PR and describe it:
    * If something is modified from the existing comparison, tell us the reason that made you to change that.
    * If a feature is added, then add an issue link that describes the feature for the specific framework.
- Push the PR.

# License

The MIT [License](https://github.com/speedwheel/awesome-go-web-frameworks/blob/master/LICENSE).
