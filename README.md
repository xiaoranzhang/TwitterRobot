# TwitterRobot
Author：Shawn

#创意来源：
新浪微博上有个自动报时的微博账号：古城钟楼。
这个账号每天什么也不做，只是到了整点就自动发布微博报时。
截至2015年5月28日，这个神奇的账号已经发布了12000+的报时微博，吸引了接近50万的粉丝关注。
当然它不是第一个，新浪微博上还有一个元老级的报时微博：big_ben_clock，至今已经发布了超过30000条的报时信息。

(⊙v⊙)嗯。。这种微博真的很傻。。
没错，当然不是人在发微博，不然一个人每天啥也不做只是在微博上发报时，不是很LOW么。
实际上原理很简单，就是几行计算机代码，再加上一个能24小时运行的服务器而已。

#用PYTHON编写twitter的报时微博：
Life is short, you need python。
得益于Github上的开源项目:TwitterAPI,这个玩具性质的twitter报时代码才有可能实现，在此表示感谢。
由于是玩具性质，也没有能够24小时运转的服务器，所以在这个项目中我只能采用一种比较low的方式，来实现自动报时的一些基本功能。
这个玩具代码需要手动开启，然后需要一直占用计算机内存运行代码。我的这个项目默认的是60分钟制，即后台运行的代码每60分钟会自动往自己的Twitter账号上发布报时信息和当前时间。

#为什么是Twitter?
相比较新浪微博而言，Twitter的API授权比较简单。
我接触的python教材和爬虫项目也大多是欧美国家的材料，所以处于简单省事的考虑，我选择了用Twitter进行我的实验。
ENJOY...

