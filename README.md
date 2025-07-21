# company-info-serve
企业工商信息查询MCP服务

# 高灯科技-企业工商信息 MCP 服务文档

## 企业工商信息MCP Server提供以下核心功能：

- 企业工商信息查询
- 企业名称模糊搜索
- 企业软件著作权信息查询
- 企业商标信息查询
- 企业专利信息查询
- 企业司法涉诉信息查询

## 服务特点
- 无须注册：配置后马上即可使用
- 实时更新：经营状态、电话号码等数据源动态更新
- 精准查询：支持通过企业全称/注册号/社会统一信用代码任意一种方式查询
- 覆盖信息全：整合企业工商注册、股东结构、高管信息等核心字段

## 如何使用 高灯科技-企业工商信息 MCP 服务？

完成部署后可直接使用

### 部署方式（Streamable Http）

```
{
  "mcpServers": {
    "GD-company-info-server": {
      "url": "https://mcp.golcer.com/mcp/"
    }
  }
}
```

查询服务由[高灯科技Goldentec](https://www.goldentec.com/ "高灯科技Goldentec")提供。
