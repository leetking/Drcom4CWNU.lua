# web登录的lua实现

使用lua的优势:
1. 方便放到路由器
2. 运行快啊!
3. 方便和C集成

## 使用

1. 使用luarocks来安装
  ```shell
  $ luarocks install cwnu-drcom
  ```
2. 修改安装目录下的`config.lua`，填写正确的用户名和密码
  ```shell
  $ luarocks show cwnu-drcom
  ```
  查看到`config.lua`所在位置，修改他!
3. 运行
  ```shell
  $ drcom
  ```

## 依赖
- lua >= 5.1
- luasocket
- md5
