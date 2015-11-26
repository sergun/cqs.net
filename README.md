# CQS.NET[![Build status](https://ci.appveyor.com/api/projects/status/r6inrwvd2ubsqv5m?svg=true)](https://ci.appveyor.com/project/sergun/cqs-net) [![Nuget version](https://img.shields.io/nuget/v/CQS.NET.svg)](https://www.nuget.org/packages/CQS.NET)Lightweight library to implement CQS principle with .NET applications. **CQS (command–query separation)** - is a principle that defines data model of a system in terms of queries and commands:* **Commands** affecting state of object and provide a simple way to execute a single operation in terms of domain model.* **Queries** allows to query information from a data source without affecting it's state.More detailed explanation of CQS principle at [Wikipedia](http://en.wikipedia.org/wiki/Command%E2%80%93query_separation).When we're working on out projects we noticed that there is some a bit more complicated logic on top of commands and queries. Usually this is a sequence of steps to run queries and commands. We called this **Workflow** and I added it here as well.* **Workflow** represents single user's scenario. It could contain sequence of calling queries/commands.# Usage1. [Initial setup](//github.com/sergun/cqs.net/wiki/Initial-setup)2. [Commands](//github.com/sergun/cqs.net/wiki/Commands)3. [Queries](//github.com/sergun/cqs.net/wiki/Queries)4. [Workflow](//github.com/sergun/cqs.net/wiki/Workflows)# Contributors- [Sergey Zwezdin](http://zwezdin.com/)# LicenseCode released under the MIT license.