# pot-app-translate-plugin-siliconflow

Siliconflow(硅基流动)翻译插件 - 一个为pot-app开发的翻译插件

## 简介
这是一个基于Silicon API的翻译插件，支持多语言翻译，提供高质量的翻译结果。

## 前置要求
- [pot-app](https://github.com/pot-app/pot-app) - 请先下载并安装pot-app
- [硅基流动官网](https://cloud.siliconflow.cn/)

## 功能特点
- 支持多种语言之间的互译
- 提供专业、流畅的翻译结果

## 安装方法
1. 在pot-app中点击"偏好设置"
2. 选择"服务设置"
3. 点击"翻译-添加外部插件"
4. 选择本插件的发布包进行安装

## 配置说明
1. 选择翻译模型, 默认`THUDM/GLM-4-32B-0414`
2. (必需) 输入你的Siliconflow API密钥
3. (非必需) 设置温度, 默认`0.3`
4. (非必需) 选择是否流式输出, 默认`开启`
5. (非必需) 设置最大tokens, 默认`2048`

## 使用说明
安装并配置完成后，在pot-app的翻译引擎列表中选择"siliconflow"即可使用。

## 注意事项
- 请妥善保管你的API密钥
- 翻译服务需要联网使用
