# Telegram如何搭建双向机器人？

------------------------------------

首先，先说明一下双向机器人的用途：

1.双向机器人是Telegram官方允许的一种沟通方式，可以避免我们被对方spam或者是被Telegram防骚扰机制误杀

2.使用双向机器人，可以帮助一些有事情找我们，但是又不能够私聊的人，那些被限制私聊的，可以通过双向机器人来进行传话，当然是对方得有双向机器人，搭建完双向机器人之后，一般情况下，讲双向机器人，给挂到简介里面就没有问题了，这样子别人需要私聊你的时候，点一下你简介，就能够看到双向机器人，这样子就避免了无效沟通的情况发生

------------------------------------

搭建双向机器人的步骤：

    1.找到官方的创建机器人的Bot，官方创建机器人的bot：https://t.me/BotFather

    2.点开机器人,找到菜单选项，然后选择/newbot，就是创建新的机器人

    3.选择/newbot之后，会出现如下提示:Alright, a new bot. How are we going to call it? Please choose a name for your bot.

    4.这里输入XXX的传话筒（XXX是个示例，不是叫你照着打上去，这里可以自定义的，你想命名成什么就是什么）

    5.输入完上面的步骤之后，下一步会出现这个:Good. Now let's choose a username for your bot. It must end in `bot`. Like this, for example: TetrisBot or tetris_bot.

    6.这里输入XXX_bot就可以了，（XXX是个示例，不是叫你照着打上去，这里可以自定义的，你想命名成什么就是什么）

------------------------------------

这里的第一个大步骤，创建机器人已经完毕了，第二步就是将创建好的机器人托管到云端去

------------------------------------

![image](/img/创建机器人步骤1.png)

------------------------------------

     7.找到托管机器人到云端的Bot：https://t.me/sxBot

     8.打开机器人之后，第一步点击菜单，然后选择/start 开始使用，然后选择添加机器人，将你在第一个创建机器人那里得出的token复制下来，然后将它粘贴到这个机器人这里就行了

![image](/img/创建机器人步骤2.png)

------------------------------------