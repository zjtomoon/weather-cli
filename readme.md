# 实时天气系统命令行工具

## 效果展示

![效果展示](./imgs/效果展示.png)

## cargo项目依赖：

+ `structopt`

+ `exitfailure`

+ `serde `

+ `serde_json`

+ `serde_derive`

+ `reqwest`

+ `tokio`

+ `chrono`

## cargo配置

```toml
[package]
name = "weather-cli"
version = "0.1.0"
edition = "2018"

# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

[dependencies]
structopt = "0.3.21"
exitfailure = "0.5.1"
serde = "1.0.114"
serde_json = "1.0.56"
serde_derive = "1.0.114"
reqwest = {version = "0.11",features = ["json"]}
tokio = {version = "1",features = ["full"]}
chrono = { version = "0.4", features = ["serde"] }
```

## 说明

使用的是[openweathermap](https://openweathermap.org/)的api来获取各大城市实时的天气情况。


