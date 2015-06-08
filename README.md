# AndroidSQLWrapper
A query wrapper for building and executing queries on Android DBs and Content Providers

A personal project for handling queries in my future Android projects.  Using Github as a backup for it, though it isn't meant for use by anyone else.

The purpose of this is to be able to create SQLite and Content Provider queries as objects rather than using a StringBuilder.  The advantage being that in the future, I won't have to worry about keeping the parenthesis, commas, quotes, etc. straight while building the query strings up.  It should also be able to easily change the database layer between SQLite, ContentProviders, and other databases using the same objects.

This is not meant to be a fully comprehensive replacement for all possible SQL statements and features, but should provide basic functionality.
