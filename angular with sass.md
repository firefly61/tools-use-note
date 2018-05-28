### angular 使用 sass

一、在项目中安装sass

    npm install node-sass --save-dev
    npm install sass-loader --save-dev
  
二、修改 *.angular-cli.json* 配置文件

    "styles": [
          "styles.scss"
        ],
    "defaults": {
      "styleExt": "scss",
      "component": {}
    }
    
    以及 .scss文件，详情请查阅sass官方API。：）
