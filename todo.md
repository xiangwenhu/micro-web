- [x] 页面刷新问题 => cookie 识别
- [x] header 传递额外参数问题 
  1. 静态的通过proxy配置
  2. 动态的比如 authorization 的 token
- [x] 请求数据格式问题    
  * json
  * x-www-form-urlencoded
  * FormData 会多出临时文件
- [x] 代理额外的 headers, body , query 等等   
    headers 支持   
    body 未支持
- [ ] ACL 如何接入   
    变通方便，请求acl带配置属性
- [x] 支持存储数据 
  - 登录后 session/cookie
- [ ] Action 抽象一些操作
  - session 存值，删除，清除
  - cookie 存值， 删除
  - header 设置
  - body filter
  - body merge
  - body remap
- [ ] 代理返回结果Filter
- [ ] 支持App的全局配置
- [ ] Handler 分为 谓词 + action？
- [ ] service worker支持？
- [ ] 多站同时运行   
      通过重新映射header的属性值，
