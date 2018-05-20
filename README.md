[![Build Status](https://travis-ci.com/fenghuang-js/fenghuang-orm.svg?branch=master)](https://travis-ci.com/fenghuang-js/fenghuang-orm)
[![Coverage Status](https://coveralls.io/repos/github/fenghuang-js/fenghuang-core/badge.svg?branch=master)](https://coveralls.io/github/fenghuang-js/fenghuang-core?branch=master)

# Fenghuang-Orm

Orm for the Fenghuang Platform

For more details about the Fenghuang Platform see [fenghuang-core](https://github.com/fenghuang-js/fenghuang-core)

Much like the rest of the platform this component is in early development.

**ORM Development guidelines**
 - ORM Should be generic and database connector agnostic
 - ORM Should provide an abstract database connector
 - ORM Should provide a database connector registry and allow for multiple instances
 - The Sequelize API should be used as a reference implementation for inspiration. Especially the query language
 - Multi-Tenant, Optimisitic Locking, Soft-Delete should be available and turned on by default (But not mandatory)
