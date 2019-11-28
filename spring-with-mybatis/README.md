## profile

在resource中可以配置多套环境的文件。启动服务的时候，可以基于环境去加载不同的配置

```shell script
SPRING_PROFILES_ACTIVE=dev gradle bootRun
```

## 测试

* SpringFramework test + RestAssured - API集成测试
* junit5 + mockito - service测试
* @MybatisTest，@DataJpaTest - 数据库存取逻辑测试

## 数据库
* docker compose 启动本地数据库
* 使用H2，HDB，其他embedded数据库