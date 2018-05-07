---
title: "Generate a C# class definition from a SQL Server Table"
categories:
  - reminder
tags:
  - generate
---
SQL code to generate a C# class definition from a SQL Server table, code originally from [stackoverflow][so-sql-answer], amended by taking into account the comments and the [SQL Server Data Type Mappings][sql-server-mappings].

<script src="https://gist.github.com/petreturcu/55ed01e219606d628699384b7582431b.js"></script>

This is useful when working with a data store that was previously defined for quickly generating the classes that would sit behind your repository or DAL.

[so-sql-answer]: https://stackoverflow.com/questions/5873170/generate-class-from-database-table
[sql-server-mappings]: https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/sql-server-data-type-mappings
