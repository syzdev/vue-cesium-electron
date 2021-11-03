# vue-cesium-electron

一个基于Vue的简易Cesium开发模板

## 效果

![demo](/readme_images/demo.png)

## 项目初始化

```
npm install
```

补全`src/common/js/config.js`中的`Token`信息（Cesium Ion Token和天地图Token）：

- `CesiumIonDefaultAccessToken`：前往 https://cesium.com/ 中注册账号，[详细教程](https://syzdev.cn/2021/08/10/注册Cesiumion教程/)，并且创建`Token`；
- `TianDiTuToken`：前往 https://uums.tianditu.gov.cn/register 中注册账号，[详细教程](https://syzdev.cn/2021/08/11/注册天地图Token教程/)，并且创建`Token`。

### 编译

```
npm run electron:serve
```

### 打包
```
npm run electron:build
```

打包后会在项目目录下生成`dist_electron`文件夹，再打开其中的`win-unpacked`文件夹，该文件夹内就是window中的可执行程序。

