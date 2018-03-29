# GetWxUser

微信公众平台OAuth2.0网页授权，获取用户信息类封装demo

这个文件微信授权使用的是OAuth2.0授权的方式。主要有以下简略步骤：

　　第一步：判断有没有code，有code去第三步，没有code去第二步

　　第二步：用户同意授权，获取code

　　第三步：通过code换取网页授权access_token

　　第四步：使用access_token获取用户信息
