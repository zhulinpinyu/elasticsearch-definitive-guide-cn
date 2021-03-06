# Summary

* [Introduction](README.md)
* [入门](010_Intro/00_README.md)
   * [是什么](010_Intro/05_What_is_it.md)
   * [安装](010_Intro/10_Installing_ES.md)
   * [API](010_Intro/15_API.md)
   * [文档](010_Intro/20_Document.md)
   * [索引](010_Intro/25_Tutorial_Indexing.md)
   * [搜索](010_Intro/30_Tutorial_Search.md)
   * [聚合](010_Intro/35_Tutorial_Aggregations.md)
   * [小结](010_Intro/40_Tutorial_Conclusion.md)
   * [分布式](010_Intro/45_Distributed.md)
   * [结语](010_Intro/50_Conclusion.md)
* [分布式集群](020_Distributed_Cluster/00_Intro.md)
   * [空集群](020_Distributed_Cluster/05_Empty_cluster.md)
   * [集群健康](020_Distributed_Cluster/10_Cluster_health.md)
   * [添加索引](020_Distributed_Cluster/15_Add_an_index.md)
   * [故障转移](020_Distributed_Cluster/20_Add_failover.md)
   * [横向扩展](020_Distributed_Cluster/25_Scale_horizontally.md)
   * [更多扩展](020_Distributed_Cluster/30_Scale_more.md)
   * [应对故障](020_Distributed_Cluster/35_Coping_with_failure.md)
* [数据](030_Data/00_Intro.md)
   * [文档](030_Data/05_Document.md)
   * [索引](030_Data/10_Index.md)
   * [获取](030_Data/15_Get.md)
   * [存在](030_Data/20_Exists.md)
   * [更新](030_Data/25_Update.md)
   * [创建](030_Data/30_Create.md)
   * [删除](030_Data/35_Delete.md)
   * [版本控制](030_Data/40_Version_control.md)
   * [局部更新](030_Data/45_Partial_update.md)
   * [Mget](030_Data/50_Mget.md)
   * [批量](030_Data/55_Bulk.md)
   * [结语](030_Data/60_Conclusion.md)
* [分布式增删改查](040_Distributed_CRUD/00_Intro.md)
   * [路由](040_Distributed_CRUD/05_Routing.md)
   * [分片交互](040_Distributed_CRUD/10_Shard_interaction.md)
   * [新建、索引和删除](040_Distributed_CRUD/15_Create_index_delete.md)
   * [检索](040_Distributed_CRUD/20_Retrieving.md)
   * [局部更新](040_Distributed_CRUD/25_Partial_updates.md)
   * [批量请求](040_Distributed_CRUD/30_Bulk_requests.md)
   * [批量格式](040_Distributed_CRUD/35_Bulk_format.md)
* [搜索](050_Search/00_Intro.md)
   * [空搜索](050_Search/05_Empty_search.md)
   * [多索引和多类型](050_Search/10_Multi_index_multi_type.md)
   * [分页](050_Search/15_Pagination.md)
   * [查询字符串](050_Search/20_Query_string.md)
* [映射和分析](052_Mapping_Analysis/00_Intro.md)
   * [数据类型差异](052_Mapping_Analysis/25_Data_type_differences.md)
   * [确切值对决全文](052_Mapping_Analysis/30_Exact_vs_full_text.md)
   * [倒排索引](052_Mapping_Analysis/35_Inverted_index.md)
   * [分析](052_Mapping_Analysis/40_Analysis.md)
   * [映射](052_Mapping_Analysis/45_Mapping.md)
   * [复合类型](052_Mapping_Analysis/50_Complex_datatypes.md)
* [结构化查询](054_Query_DSL/00_Intro.md)
   * [请求体查询](054_Query_DSL/55_Request_body_search.md)
   * [结构化查询](054_Query_DSL/60_Query_DSL.md)
   * [查询与过滤](054_Query_DSL/65_Queries_vs_filters.md)
   * [重要的查询子句](054_Query_DSL/70_Important_clauses.md)
   * [过滤查询](054_Query_DSL/75_Queries_with_filters.md)
   * [验证查询](054_Query_DSL/80_Validating_queries.md)
   * [结语](054_Query_DSL/85_Conclusion.md)
* [排序](056_Sorting/00_Intro.md)
   * [排序](056_Sorting/85_Sorting.md)
   * [字符串排序](056_Sorting/88_String_sorting.md)
   * [相关性](056_Sorting/90_What_is_relevance.md)
   * [字段数据](056_Sorting/95_Fielddata.md)
* [分布式搜索](060_Distributed_Search/00_Intro.md)
   * [查询阶段](060_Distributed_Search/05_Query_phase.md)
   * [匹配阶段](060_Distributed_Search/10_Fetch_phase.md)
   * [搜索选项](060_Distributed_Search/15_Search_options.md)
   * [扫描和滚动](060_Distributed_Search/20_Scan_and_scroll.md)
* [索引管理](070_Index_Mgmt/00_Intro.md)
   * [创建删除](070_Index_Mgmt/05_Create_Delete.md)
   * [设置](070_Index_Mgmt/10_Settings.md)
   * [配置分析器](070_Index_Mgmt/15_Configure_Analyzer.md)
   * [自定义分析器](070_Index_Mgmt/20_Custom_Analyzers.md)
   * [映射](070_Index_Mgmt/25_Mappings.md)
   * [根对象](070_Index_Mgmt/30_Root_Object.md)
   * [元数据中的source字段](070_Index_Mgmt/31_Metadata_source.md)
   * [元数据中的all字段](070_Index_Mgmt/32_Metadata_all.md)
   * [元数据中的ID字段](070_Index_Mgmt/33_Metadata_ID.md)
   * [动态映射](070_Index_Mgmt/35_Dynamic_Mapping.md)
   * [自定义动态映射](070_Index_Mgmt/40_Custom_Dynamic_Mapping.md)
   * [默认映射](070_Index_Mgmt/45_Default_Mapping.md)
   * [重建索引](070_Index_Mgmt/50_Reindexing.md)
   * [别名](070_Index_Mgmt/55_Aliases.md)
* [深入分片](075_Inside_a_shard/00_Intro.md)
   * [使文本可以被搜索](075_Inside_a_shard/20_Making_text_searchable.md)
   * [动态索引](075_Inside_a_shard/30_Dynamic_indices.md)
   * [近实时搜索](075_Inside_a_shard/40_Near_real_time.md)
   * [持久化变更](075_Inside_a_shard/50_Persistent_changes.md)
   * [合并段](075_Inside_a_shard/60_Segment_merging.md)
* [结构化搜索](080_Structured_Search/00_structuredsearch.md)
   * [查询准确值](080_Structured_Search/05_term.md)
   * [组合过滤](080_Structured_Search/10_compoundfilters.md)
   * [查询多个准确值](080_Structured_Search/15_terms.md)
   * [包含，而不是相等](080_Structured_Search/20_contains.md)
   * [范围](080_Structured_Search/25_ranges.md)
   * [处理 Null 值](080_Structured_Search/30_existsmissing.md)
   * [缓存](080_Structured_Search/40_bitsets.md)
   * [过滤顺序](080_Structured_Search/45_filter_order.md)
