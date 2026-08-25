最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 canary 金丝雀部署实操
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8233420.sHtMl

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0452051.sHtMl

原标题：入门实践：简单错误码设计与使用规范
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1863491.sHtMl

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8406182.sHtMl

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2924926.sHtMl

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0628207.sHtMl

原标题：批量数据处理脚本编写技巧
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4586978.sHtMl

原标题：方案对比：单体、微服务、模块化单体取舍
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7739066.sHtMl

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8345169.sHtMl

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2608155.sHtMl

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2913961.sHtMl

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9938907.sHtMl

原标题：golang yaml 解析配置加载实操
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3044319.sHtMl

原标题：不必要字符转义关闭业务异常
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3327803.sHtMl

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9420970.sHtMl

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3088722.sHtMl

原标题：golang redis 布隆过滤器安装使用
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6899111.sHtMl

原标题：简易网关请求路由过滤模拟
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9991518.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2229597.sHtMl

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5139872.sHtMl

原标题：golang kafka 核心概念分区副本
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7312443.sHtMl

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7426419.sHtMl

原标题：Docker 网络模式容器互通设置
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3261616.sHtMl

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3685673.sHtMl

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1533102.sHtMl

原标题：快速入门GraphQL基础查询语法示例
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8477133.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6531288.sHtMl

原标题：golang 系统设计秒杀防超卖方案
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5317480.sHtMl

原标题：不必要字符转义关闭业务异常
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7897936.sHtMl

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4423496.sHtMl

原标题：系统字符集统一乱码修复
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9233869.sHtMl

原标题：golang 系统设计日志级别业务使用原则梳理
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5585790.sHtMl

原标题：golang 链路 traceId 透传中间件
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2876497.sHtMl

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7515764.sHtMl

原标题：golang 系统设计分布式会话方案对比
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8310191.sHtMl

原标题：安全笔记：CSP内容安全策略配置实践
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0762305.sHtMl

原标题：golang 灰度权重流量分发简单实现
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5550578.sHtMl

原标题：语义化版本依赖管理防错乱
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7540231.sHtMl

原标题：Docker Compose 一键搭建本地栈
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2689008.sHtMl

原标题：Nginx 静态代理负载均衡全套配置
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3021247.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang ci 流水线自动部署 k8s 示例
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3097344.sHtMl

原标题：方案设计：分布式分页查询架构难点处理
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6743427.sHtMl

原标题：golang redis 主从复制哨兵原理
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7185071.sHtMl

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0754901.sHtMl

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4925343.sHtMl

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1717271.sHtMl

原标题：架构笔记：数据库连接池架构参数调优思路
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9969718.sHtMl

原标题：nodejs redis 缓存业务实战
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5847566.sHtMl

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2767940.sHtMl

原标题：文件句柄耗尽资源泄露处理
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2978472.sHtMl

原标题：轻量 API 后端接口服务快速开发
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3664985.sHtMl

原标题：新手教程：本地环境变量配置全流程
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4126281.sHtMl

原标题：前端水印防信息泄露实现
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3463691.sHtMl

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0259471.sHtMl

原标题：golang redis 连接池参数最佳值
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1724235.sHtMl

原标题：golang 项目 docker compose 本地调试
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5235726.sHtMl

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7127830.sHtMl

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0430856.sHtMl

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0427784.sHtMl

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3535134.sHtMl

原标题：golang 静态文件服务搭建教程
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7213644.sHtMl

原标题：Cookie Session 会话状态管理
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0263683.sHtMl

原标题：前端虚拟列表大数据渲染优化
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1116385.sHtMl

原标题：Security：密码存储哈希加盐最佳实践
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5297350.sHtMl

原标题：优化实践：Redis性能调优，避免大key热key
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7978197.sHtMl

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1470519.sHtMl

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6765029.sHtMl

原标题：golang redis stream 消息队列实践
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7155083.sHtMl

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3723017.sHtMl

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5986898.sHtMl

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8944839.sHtMl

原标题：方案对比：同步调用vs异步消息业务选型
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2118448.sHtMl

原标题：golang 令牌桶限流中间件 gin
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0324310.sHtMl

原标题：集成测试业务流程编写示例
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1354192.sHtMl

原标题：axios 二次封装请求拦截处理
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1750949.sHtMl

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2943802.sHtMl

原标题：实战：多版本SDK兼容业务改造实践
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0616711.sHtMl

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4805436.sHtMl

原标题：网关超时时间调优后端等待
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2208831.sHtMl

原标题：golang goroutine 池任务调度
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5272265.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9926650.sHtMl

原标题：Performance：数据库索引优化常见错误案例
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4164814.sHtMl

原标题：golang k8s cronjob 定时任务配置
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4534461.sHtMl

原标题：golang 优雅处理系统信号 SIGINT
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8944146.sHtMl

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5901138.sHtMl

原标题：golang websocket 服务端开发
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5056180.sHtMl

原标题：开源实践：给开源项目写单元测试贡献代码
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0325136.sHtMl

原标题：golang viper 配置热更新实操
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3389705.sHtMl

原标题：Nginx 静态代理负载均衡全套配置
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2203038.sHtMl

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3170850.sHtMl

原标题：环境变量不生效问题修复
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6047785.sHtMl

原标题：时间精度统一业务判断修复
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9231500.sHtMl

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1824618.sHtMl

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2372686.sHtMl

原标题：Performance：避免大报文，减少内存占用优化
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2579514.sHtMl

原标题：golang 系统设计批量处理优化业务性能
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1208839.sHtMl

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2659709.sHtMl

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8893907.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6788006.sHtMl

原标题：Practice：实现批量任务失败断点续跑实践
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1808910.sHtMl

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6385355.sHtMl

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6437988.sHtMl

原标题：golang 系统设计指标埋点代码低侵入实现
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7860154.sHtMl

原标题：Hands‑on：简易短链接服务完整开发实践
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8846079.sHtMl

原标题：golang 系统设计 pr 评审合并完整流程
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0075194.sHtMl

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7587021.sHtMl

原标题：golang 接口返回统一封装工具
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9324548.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5398176.sHtMl

原标题：express 请求参数校验处理
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9575166.sHtMl

原标题：golang 链路 traceId 透传中间件
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2719633.sHtMl

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1956606.sHtMl

原标题：service‑worker 离线缓存实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6705077.sHtMl

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5790768.sHtMl

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3076545.sHtMl

原标题：golang 系统设计参数校验统一处理方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0133191.sHtMl

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7981613.sHtMl

原标题：Hands‑on：简易图片压缩处理服务demo
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4289422.sHtMl

原标题：跨库查询性能优化处理
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7466877.sHtMl

原标题：golang 系统设计技术方案文档模板参考
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8081845.sHtMl

原标题：golang docker 多阶段构建 go 镜像
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3474054.sHtMl

四、架构设计｜Architecture
原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3478681.sHtMl

原标题：调优方案：前端静态资源打包性能体积优化
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0890424.sHtMl

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7521919.sHtMl

原标题：Security：Docker镜像安全扫描漏洞修复
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.m9eza5.asia/blog/2217813.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3325621.sHtMl

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1215343.sHtMl

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://zhishi.m9eza5.asia/blog/4916469.sHtMl

原标题：部署实践：Nginx高可用配置方案实践
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1653343.sHtMl

原标题：golang es 查询语句 DSL 实操
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://zhishi.m9eza5.asia/blog/5865199.sHtMl

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://zhishi.m9eza5.asia/blog/1980853.sHtMl

原标题：golang redis zset 排行榜业务实现
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://zhishi.m9eza5.asia/blog/0494601.sHtMl

原标题：golang 系统设计多租户数据隔离方案
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://zhishi.m9eza5.asia/blog/7732457.sHtMl

原标题：JSON XML 数据解析处理示例
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3401316.sHtMl

原标题：浏览器内存泄漏排查前端页面
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://zhishi.m9eza5.asia/blog/8270616.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://zhishi.m9eza5.asia/blog/3142486.sHtMl

原标题：golang 系统设计排行榜几种实现
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://zhishi.m9eza5.asia/blog/6383907.sHtMl

原标题：golang k8s 网络策略网络隔离设置
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9137758.sHtMl

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://zhishi.m9eza5.asia/blog/9979248.sHtMl

?
