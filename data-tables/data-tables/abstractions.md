---
description: >-
  We construct customs tables which cover the entirety of a type of activity on
  the blockchain and thereby enable you to effortlessly aggregate lots of data
  with as little friction as possible.
---

# Abstractions

## What are abstractions?

Abstractions are custom tables that are maintained by Team Dune and our community. They allow you to gain access to more complex SQL operators like creating your own tables, looping through values or other operations that are more catered towards database administrators. This sometimes is necessary to aggregate the on-chain data or simplify the process of querying for data.

This public [github repository](https://github.com/duneanalytics/abstractions) hosts the logic to construct the tables and views.

##  Which abstractions are there?

You can check for existing abstractions in our [public github repository](https://github.com/duneanalytics/abstractions). You can generally divide them into 2 distinct categories. 



### Sector Abstractions

Sector Abstractions are tables like dex.trades, erc20.stablecoins, lending.borrow etc. 

These abstractions take in data from multiple contracts and projects, standardize the data across them and therefore make it very easy to query for this data and compare the metrics of different projects with each other.

Most of the [sector](../../about/usecases/sector-dashboards.md) Dashboards depend on sector abstractions. This introduces an interesting dynamic in which projects can easily get their data into these dashboards by making a pull request to our public [github repo](https://github.com/duneanalytics/abstractions).  
  
Team Dune and the community are always improving on these sector abstractions, all new additions to existing ones are always welcome.



### Project Abstractions

Sometimes it can be useful for projects to assemble their data into one neat table that has all the data they need in one place. To do this, you can construct views or tables in our abstractions.



## Contributing to abstractions

Our abstractions are open to all teams and projects in general, but we do reserve the right to reject pull requests. 

If you do choose to contribute to abstractions


