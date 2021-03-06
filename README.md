maiome's library of utilities
=============================

Build status: https://phabricator.maio.me/harbormaster/query/M66HrtGGrY6u/

This is a library of semi-useful and hopefully reusable utilities used within a few
of the projects that are in development under the maiome namespace.

- config.configuration -> a "simple" config reader with section promises and special types.
- connection.connection -> a structured-packet based connection client.
- connection.packets -> an extendible packet implementation for use with the other connection classes.
- connection.server -> a structure-packet based connection server.
- database.dbmapper -> a reflective/introspective ORM used for simple object relations in SQLite (and maybe others).
- database.dbtypeconv -> a series of sqlite "middlewares" to do useful type conversions.
- text.table -> relatively simple text table formatter that allows formatting of data in different ways.
- util.args -> flexible command line argument parser.
- util.names -> simple random name generator.
- util.scheduler -> a simple tick-based scheduler suitable for use in ticking event loops.
