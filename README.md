# 使用

```sh
git clone https://github.com/kongxiangyiren/alemon-appstore /opt/1panel/resource/apps/local/appstore-localApps
```

```sh
cp -rf /opt/1panel/resource/apps/local/appstore-localApps/apps/* /opt/1panel/resource/apps/local/
```

```sh
rm -r /opt/1panel/resource/apps/local/appstore-localApps
```

# 复刻说明 (github 开启 bot 推送)

## github 安装 renovate app

https://github.com/apps/renovate

## 绑定 alemon-appstore 仓库

![alt text](docs/image.png)

![alt text](docs/image-1.png)

![alt text](docs/image-2.png)

# 创建应用模板

```sh
cd apps
1panel app init -k <应用的key（仅支持英文）> -v <应用版本>
```
