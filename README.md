# hwsdc-http
华为SDC APP内httplib改装


做华为SDC相关项目时，需要做httpclient与业务服务器进行通信
由于华为做了一层隔离，需要手撸通信层，所以将开源的https://github.com/yhirose/cpp-httplib 进行了改装
具体用法和httplib用法一样，当然也可以通过注释#define HWSDC 关闭该功能，具体改过的地方也可以通过改宏查找，如有BUG 可自行解决。


如果觉得不错或者使用了 请自觉star。
