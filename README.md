### Avue
基于数据驱动视图的思想，根据json数据快速构建crud和form等组件  
依赖包:  
* axios：发送ajax数据用到的包
* element-ui：可视化UI组件
* 引入avue之前先引入上面这俩个包

#### 引入方式
```
#### CDN
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/@smallwei/avue@1.0.1/lib/theme-chalk/index.css" />

<script src="https://cdn.jsdelivr.net/npm/@smallwei/avue@1.0.1/lib/index.min.js"></script>

#### npm
npm i @smallwei/avue --save

#### yarn
yarn add @samallwei/avue --save

```

#### 使用方式
```
import Element from 'element-ui'
import axios from 'axios'
import Avue from @smallwei/avue/lib/index.js
import @smallwei/avue/lib/theme-chalk/index.css

Vue.use(Element);
Vue.use(Avue,axios)

```

#### 如何在pigx-ui中升级avue
```
1.第一步  
删除packages里面的avue-cli  
2.第二步  
npm i @smallwei/avue —save  
3.第三步  
import Avue from @smallwei/avue/lib/index.js  
import @smallwei/avue/lib/theme-chalk/index.css  

```


#### 运行例子
```
npm run dev
```

#### 打包例子
```
npm run dev:build
```

#### 打包部署
```
npm run dist
```

#### 打包样式
```
npm run build:theme
```

#### 打包源码
```
npm run build
```

#### 代码检测
```
npm run lint
```