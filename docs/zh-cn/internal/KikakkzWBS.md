## KK的项目总览

### 季度目标 :triangular_flag_on_post::triangular_flag_on_post::triangular_flag_on_post:

- Crypto More官网上线 :blue_heart:
- Hashage上线 :blue_heart:
- web3eye.io上线 :blue_heart:
- 测试框架（API测试，前端自动测试，系统功能测试） :blue_heart:
- 分布式事务改造 :blue_heart:
- 操作日志 :blue_heart:
- 开始整合机房系统 :blue_heart:
- FIL-Peggy与FVM一起上线 :broken_heart:
- Filecoin Lotus DC功能开发 - done :green_heart:

### 上周目标 :triangular_flag_on_post:

- [ ] smoketest V0.1 - 唐红/大强/KK - 4/22 （后端table/CRUD/实现重构，前端测试计划管理，good-manager模块跑通）:blue_heart:
- [X] 用户模块handler/options pattern重构、mgr/mw合并 - KK - 4/22 - done :green_heart:
- [ ] handler/options pattern重构、mgr/mw合并WBS - KK - 4/22:blue_heart:
- [ ] staker-manager dtm调用/PUBSUB重构WBS - KK - 4/22:blue_heart:
- [ ] staker-manager充值模块dtm调用/PUBSUB重构 - KK - 4/22:blue_heart:
- [ ] web3eye.io offline/online分离架构Coding完成 - 姜杰 - 4/22:blue_heart:
- [ ] FIL-Peggy V0.1收益核算接口/收益核算接口GAS优化 - P1 - 4/7 - 4/14 - 4/22:blue_heart:
- [ ] HashAge网页应用设计 - KK/FZ - 4/20:blue_heart:
- [ ] 官网产品页文案确定 - 雪冬/KK - 4/22:blue_heart:
- [ ] 操作日志prototype确定 - KK - 4/22:blue_heart:
- [ ] Filecoin 1.22升级 - KK - 4/22:blue_heart:
- [ ] boost/swan boost切换/瓶颈确认 - 唐红 - 4/22:blue_heart:
- [X] 文档站上线 - 唐红 - 4/22 - done:green_heart:
- [X] 铁鱼上线部署 - 王 - 4/20 - done:green_heart:
- [X] More铁鱼提现支持 - 唐红/姜杰 - 4/20 - done:green_heart:

### 本周目标 :triangular_flag_on_post:

- [ ] smoketest V0.1 - 唐红/大强/KK - 4/22 （后端table/CRUD/实现重构，前端测试计划管理，good-manager模块跑通） - 4/28:blue_heart:
- [X] handler/options pattern appuser-gateway重构 - KK - 4/22 - 4/28 - done:green_heart:
- [ ] handler/options pattern重构、mgr/mw合并WBS - KK - 4/22 - 4/28:blue_heart:
- [ ] staker-manager dtm调用/PUBSUB重构WBS - KK - 4/22 - 4/28:blue_heart:
- [ ] staker-manager充值模块dtm调用/PUBSUB重构 - KK - 4/22 - 4/28:blue_heart:
- [ ] web3eye.io offline/online分离架构Coding完成 - 姜杰 - 4/22 - 4/28:blue_heart:
- [ ] FIL-Peggy V0.1收益核算接口/收益核算接口GAS优化 - P1 - 4/7 - 4/14 - 4/22 - 4/28:blue_heart:
- [ ] HashAge网页应用设计 - KK/FZ - 4/20 - 4/28:blue_heart:
- [ ] 官网产品页文案确定 - 雪冬/KK - 4/22 - 4/28:blue_heart:
- [ ] 操作日志prototype确定 - KK - 4/22 - 4/28:blue_heart:
- [ ] Filecoin 1.22升级 - KK - 4/22 - 4/28:blue_heart:
- [ ] boost/swan boost切换/瓶颈确认 - 唐红 - 4/22 - 4/28:blue_heart:

### Crypto More :point_up:

- 测试框架引入 - 4/20 - 唐红 - 4/22 - 4/28 :blue_heart:
  - smoketest服务 - 4/22 - 4/28
    - GW API实现重构 - done
      - [X] 用例前置条件、后置条件GW、MW实现 - 4/23 - done
      - [ ] middleware和gateway自测 - 4/25
  - 前端 - KK - 4/22 - 4/28
    - [ ] 测试计划 - KK - 4/22 - 4/28
    - [ ] 执行批量测试 - KK - 4/22 - 4/28
    - [ ] 报告导出
    - [ ] 测试结果更新
    - [ ] 记录引入版本，depracated版本，废弃版本
    - [ ] 可以从swagger导入测试接口

- appuser-gateway适配appuser-middleware - 4/28
  - appuser-gateway适配新appuser-middleware和PUBSUB/dtm - 4/21 - 4/28
    - [X] user - done
    - [X] app - done
    - [X] admin - done
    - [X] authing - done
    - [X] kyc - done
    - [X] role - 今天 - done
    - [X] subscriber - 今天 - done

- good-gateway - 今天
- order-gateway - 今天
- inspire-gateway - 今天
- staker-manager适配 - KK - 4/23 - 4/28 - 今天

- 官网定稿 - 4/14 - 4/20 - 4/28
  - 产品页素材整理 - 雪冬/KK/唐红/妙
    - [ ] 各项目白皮书 - 4/14 - 4/28
    - [ ] 时间线 - 4/28
  - [ ] 各项目产品页内容确定 - KK - 4/28

- docs.cryptomore.io / cryptomore.github.com - KK - 唐红 - 4/20 - 4/28
  - [X] 创建cryptomore的组织及仓库，docs - done
  - [X] 确定域名及logo - done
  - [X] 支持全局搜索/支持中英文切换 - done
  - [X] 支持日间/夜间模式切换 - done
  - [ ] 支持翻页
  - [ ] github目录只保留单层
  - [ ] 支持文档目录索引
  - [ ] 浏览路径面包屑
  - [ ] 支持contributor
  - [X] 确定目录结构
  - [ ] 文档模板
  - [ ] 向本文档站添加一个规范文档的最佳实践
  - [ ] 文档站使用规范
  - [ ] 邮件发布v1版本
