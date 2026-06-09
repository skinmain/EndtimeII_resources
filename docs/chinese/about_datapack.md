[返回目录](menu.md)
# 自定义数据包
作者为部分模组添加了数据包以达到魔改的目的（非直接修改模组文件）<br>
此外，作者通过自定义数据包添加了一些自定义结构供玩家探索（未完工）<br><br>
你可以在 **[整合包游戏目录]/config/openloader/data** 来查看数据包魔改过的内容

## 注意
***斜体名称*** 的数据包为作者制作或他人制作，**除非经过允许，否则禁止在其他整合包中使用！**<br>
部分数据包为通用内容，也就是说此类数据包可以在后续的整合包中进行复用。<br>
除非必须或整合包切断与通用架构的联系，否则不做修改。

# 数据包文件名及其介绍
* ***entity***<br>
通用数据包，用于修改实体的部分数据

* **instant_transfur**<br>
Changed mod自带数据包，用于瞬间兽化玩家以及其他被humanoid标签包含的所有实体。放在这里方便全局调用。<br>

* **itm_zombiekit_config**<br>
模组 *丧尸生存工具包* 相关

* ***loots***<br>
通用数据包，用于包含常用的战利品表，方便调用。**不建议修改**。

* **modpack_custom**<br>
整合包定制内容，用于修改一些模组数据、定制游戏内容以及修改/添加部分机制,以及定制结构和战利品表<br>
**注意：该数据包下的*cus_struc*和*custom_config_tags*文件夹及其中的内容为作者添加，禁止在其他整合包中使用**

* **str_create_easystructures_config**<br>
模组 *Create:EasyStructures* 相关

* **str_structury_config**<br>
模组 *structury* 相关

* ***structures***<br>
通用数据包，包含通用的自然结构生成及通用结构处理器，以及结构中的战利品表。

* **tectonic-datapack-v2.2.2.zip**  
*tectonic* 地形模组的数据包版本，用于缓解结构与地形的冲突