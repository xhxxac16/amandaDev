npm adduser
npm publish

更新版本：
npm version 0.1.1
npm publish


npm发布注意事项：
http://registry.npm.taobao.org没有上传的权限，需要切回npm set registry http://registry.npmjs.org
npm config set registry=http://registry.npmjs.org

版本格式：主版号.次版号.修订号，版号递增规则如下：
主版号：当你做了不相容的API 修改，
次版号：当你做了向下相容的功能性新增，
修订号：当你做了向下相容的问题修正。

先行版号及版本编译资讯可以加到「主版号.次版号.修订号」的后面，作为延伸。
npm publish --tag 0.0.1