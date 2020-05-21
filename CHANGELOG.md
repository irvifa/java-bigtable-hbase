# Changelog

## [1.15.0](https://www.github.com/googleapis/java-bigtable-hbase/compare/v1.14.0...v1.15.0) (2020-05-21)


### Features

* adding client wrapper interfaces ([#2406](https://www.github.com/googleapis/java-bigtable-hbase/issues/2406)) ([1ad48d9](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ad48d9418e4d25180ca3dc66aaefcf80e00314b))
* extend RowCell to include labels field ([#2397](https://www.github.com/googleapis/java-bigtable-hbase/issues/2397)) ([80a85fe](https://www.github.com/googleapis/java-bigtable-hbase/commit/80a85fee02958d0fbe4fb32c6c809db7c0803358))
* tune default settings to align with java-bigtable ([#2439](https://www.github.com/googleapis/java-bigtable-hbase/issues/2439)) ([4aedcd9](https://www.github.com/googleapis/java-bigtable-hbase/commit/4aedcd9a572ef5ad246628654e06d31348dfd383))


### Bug Fixes

* deadlock scenario from BulkReadVeneerApi and fixed flaky tests ([#2484](https://www.github.com/googleapis/java-bigtable-hbase/issues/2484)) ([e4cd4ef](https://www.github.com/googleapis/java-bigtable-hbase/commit/e4cd4ef7b38777d1692a15d5f2182889271f6645))
* remove duplicated cell when interleave filter is applied ([#2491](https://www.github.com/googleapis/java-bigtable-hbase/issues/2491)) ([2915bfd](https://www.github.com/googleapis/java-bigtable-hbase/commit/2915bfd5527bd6beabab264a79fa764f2e6a7629))
* to fix deleteRowRangeByPrefix for integer values above 127 ([#2511](https://www.github.com/googleapis/java-bigtable-hbase/issues/2511)) ([1ae8c03](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ae8c03f1636b18c3fb6310db61a30f6ab7e9646)), closes [#2509](https://www.github.com/googleapis/java-bigtable-hbase/issues/2509)
* updated assertions and scan for firstKeyOnlyFilter test ([#2483](https://www.github.com/googleapis/java-bigtable-hbase/issues/2483)) ([a2cbe7a](https://www.github.com/googleapis/java-bigtable-hbase/commit/a2cbe7a97c2f65bd1f2a21eaba0c8868b315d55d)), closes [#1996](https://www.github.com/googleapis/java-bigtable-hbase/issues/1996)
* **logs:** type aligned to in log statement ([#2536](https://www.github.com/googleapis/java-bigtable-hbase/issues/2536)) ([76c41ca](https://www.github.com/googleapis/java-bigtable-hbase/commit/76c41ca37986cc703a27af971012949c425fb329))


### Dependencies

* add maven-enforcer-plugin ([#2401](https://www.github.com/googleapis/java-bigtable-hbase/issues/2401)) ([1ef4b9c](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ef4b9cb23a11d630114f382080baac66fa2f26d))
* **fix:** add log4j12 to mincluster h2 tests ([#2450](https://www.github.com/googleapis/java-bigtable-hbase/issues/2450)) ([bf5ef7c](https://www.github.com/googleapis/java-bigtable-hbase/commit/bf5ef7c80dd504baa56887fbdfe975677c05ab34))
* align bigtable-hbase-1.x-mapreduce to use the same hadoop version as other 1.x modules ([#2455](https://www.github.com/googleapis/java-bigtable-hbase/issues/2455)) ([60a5f82](https://www.github.com/googleapis/java-bigtable-hbase/commit/60a5f82e3e3c9affdcaf5ae2a8b79c433b5a1a1b))
* fix undeclared used dependencies ([#2419](https://www.github.com/googleapis/java-bigtable-hbase/issues/2419)) ([d9b109f](https://www.github.com/googleapis/java-bigtable-hbase/commit/d9b109f01b53924476b0d2b8cdbe5b36ef83bdad))
* update bigtable veneer version to 1.12.2 ([#2526](https://www.github.com/googleapis/java-bigtable-hbase/issues/2526)) ([c422b07](https://www.github.com/googleapis/java-bigtable-hbase/commit/c422b07f06cb55831e2287fd6dced7ce46ea25da))
* update dependency com.google.auto.value:auto-value-annotations to v1.7.2 ([#2532](https://www.github.com/googleapis/java-bigtable-hbase/issues/2532)) ([818f435](https://www.github.com/googleapis/java-bigtable-hbase/commit/818f4354846b848307b74c4d927d73833da254e6))
* update dependency com.google.http-client:google-http-client-jackson2 to v1.35.0 ([#2507](https://www.github.com/googleapis/java-bigtable-hbase/issues/2507)) ([73f5c5e](https://www.github.com/googleapis/java-bigtable-hbase/commit/73f5c5e6ee599db681e3c27bc96fe0664db7d45e))
* update dependency org.mockito:mockito-core to v3.3.3 ([#2414](https://www.github.com/googleapis/java-bigtable-hbase/issues/2414)) ([e82bc10](https://www.github.com/googleapis/java-bigtable-hbase/commit/e82bc102f25085f3c223073d5e142f3376b0ec55))


### Documentation

* automatically update version numbers with release ([#2476](https://www.github.com/googleapis/java-bigtable-hbase/issues/2476)) ([2ad78e9](https://www.github.com/googleapis/java-bigtable-hbase/commit/2ad78e919fada035e1c6d92f056c8dbf64771f4a))
