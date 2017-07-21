# Java实现讯飞语音识别与合成功能

### 这个项目是第一个推送到码云上的Java项目，今天想着实现一下语音识别与合成功能，于是就挑选了讯飞的API接口，这里只有Java，C，Android，IOS的SDK，所以我先挑了Java的SDK，来进行二次开发，官网里有对SDK环境配置的详细说明，包括导包什么的，语音识别等功能也有详解，下载好的SDK里有几个完整的DEMO可以直接使用，我已经放到res中了，sample中有三个demo。

### MSCDemo是一个有界面的包含三种功能的完整demo，可以直接使用，我已经放到项目里了，分别是com.rain.iflyek.util和com.rain.speech两个包，互相调用，不可删除

### MsclnvisibleDemo里只是两个类，没有界面，只有简单的功能，MSCText里有个简单的菜单，可以选择音频听写，语音合成，音频是指录好的音频，语音合成的文本内容在代码里可以修改，这几个功能我都已经放到项目的com.rian.xun包里，其中的test.java是我下载的一个读取pcm录音程序的class，在MscText.java中调用。

