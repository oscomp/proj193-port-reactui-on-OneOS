# proj193-port-reactui-on-OneOS

**项目描述**

react ui框架是基于LVGL下的一个开源项目，用于支撑使用JavaScript编写LVGL。它使用react的虚拟DOM概念来操作LVGL UI组件，为用户提供简便快捷的开发体验。

one-evue是基于OneOS开发的嵌入式（embedded）vue框架，用于开发嵌入式轻应用，类VUE.JS的前端框架，也是基于OneOS操作系统上的一套应用&图形解决方案。

两者都是使用前端框架在RTOS上进行图形开发，目前one-evue已在主线可以开发嵌入式轻应用，使用onejs-evue-cli脚手架类vue开发方式。react ui框架则基于LVGL开源，并未移植到OneOS，我们的目标是移植react ui框架到OneOS，并和one-evue进行性能对比。

**源码**

[OneOS(gitee.com)](https://gitee.com/cmcc-oneos/OneOS)

[lvgl/lvgl(github.com)](https://github.com/lvgl/lvgl)

[lvgl/lv_binding_js(github.com)](https://github.com/lvgl/lv_binding_js)

### 项目导师

庞超

- Gitee chao(https://gitee.com/pc-courage)
- email pangchao@cmiot.chinamobile.com

### 难度

中等

**文档**

[LVGL documentation](https://docs.lvgl.io/8.2/)

[lvgl/lv_binding_js(github.com)](https://github.com/lvgl/lv_binding_js)

[文档中心 (10086.cn)](https://os.iot.10086.cn/v2/doc/homePage)

**License**

- Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

**预期目标**

**注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标**

**第一题：移植react ui到OneOS**

- 移植LVGL开源项目中的react ui框架到oneos；
- 输出与oneos轻应用框架one-evue的性能对比报告，如资源占用情况。

**选择该赛题的支持**  
开发套件支持：提供给参赛队伍开发套件，此开发板万耦天工板载STM32 F103芯片:144引脚，512K FLASH，支持GSM/GPRS /LORA /WIFI/蓝牙、LCD、摄像头、温湿度等模块。并具有丰富的例程demo，OneOS学院提供手把手教学视频，方便同学们上手使用。  
获奖激励：公司对获奖同学提供入职绿色通道，获得全国总决赛二等奖、三等奖的同学可以免笔试，直接进入面试环节。获得全国总决赛一等奖的同学可以直接进入终面环节。  
技术答疑指导：针对OneOS操作系统及本赛题技术要点，资深研发工程师提供专业的技术支持、指导，全程辅导技术方案的实现。  
技术资料：提供相关技术资料和对应索引，指导赛题方向。  
