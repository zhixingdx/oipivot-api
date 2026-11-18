# OIPivot API

这里发布 OIPivot 平台对业务项目开放的 Protobuf 定义和生成的 Go gRPC 客户端。Go 模块路径为 `github.com/zhixingdx/oipivot-api`。调用方在项目的 go.mod 中固定所需的发行版本，并连接已部署的平台服务。可用版本见[发行标签](https://github.com/zhixingdx/oipivot-api/tags)。

契约变更经平台源仓评审后，由自动化提交到本仓的同步 PR。每份快照附带来源提交、内容哈希及生成工具版本，记录在 `.oipivot-contracts.json`。有接口或兼容性建议，可在本仓提出 issue。配置、访问凭据和实际服务地址由部署方提供。
