# 下载 v0.3.3

<table><tr><td>
<img src="download-info.svg" width="928" alt="万物皆 Boss v0.3.3 · Java 1.21.10 · Fabric · 编译成功">
</td></tr><tr><td>
<a href="https://raw.githubusercontent.com/susu2020oxo/boos/downloads-v0.3.3/worldbosses-0.3.3-fabric-1.21.10.jar"><img src="download-mod.svg" width="928" alt="下载 MOD（JAR）"></a>
</td></tr><tr><td>
<a href="https://raw.githubusercontent.com/susu2020oxo/boos/downloads-v0.3.3/worldbosses-0.3.3-install.zip"><img src="download-zip.svg" width="928" alt="下载完整 ZIP 安装包"></a>
</td></tr><tr><td>
<a href="https://github.com/susu2020oxo/boos/blob/downloads-v0.3.3/worldbosses-0.3.3-fabric-1.21.10.jar?raw=true">GitHub 云仓库备用下载 ↗</a>
</td></tr></table>

**v0.3.3：Boss 生命值 ×6，攻击伤害 ×3（相对 v0.3.2）。**

全部 68 种 Boss 包含友好、中立与敌对生物：猪／牛 96 HP、羊 72 HP、鸡 48 HP、僵尸 300 HP、铁傀儡 720 HP、监守者 3000 HP。友好生物保持原版行为。

近战、远程、爆炸和技能命中伤害统一提高 3 倍，原版难度、护甲、盾牌及受伤间隔继续生效。无攻击者归属的中毒、凋零、燃烧持续伤害沿用原版。爆炸方块破坏强度仍为 200。

旧存档自动升级并保留受伤比例，反复加载不会叠加或自动补满血，无需新建存档或删除配置。玩家和原本排除的水生生物不套用倍率。保留食物每次消耗 1 个的修复及旧版模型、掉落物与生成规则。

- [直接下载 JAR](https://raw.githubusercontent.com/susu2020oxo/boos/downloads-v0.3.3/worldbosses-0.3.3-fabric-1.21.10.jar) · [完整 ZIP（含 Fabric API）](https://raw.githubusercontent.com/susu2020oxo/boos/downloads-v0.3.3/worldbosses-0.3.3-install.zip)
- [JAR 备用入口](https://github.com/susu2020oxo/boos/blob/downloads-v0.3.3/worldbosses-0.3.3-fabric-1.21.10.jar?raw=true) · [ZIP 备用入口](https://github.com/susu2020oxo/boos/blob/downloads-v0.3.3/worldbosses-0.3.3-install.zip?raw=true)
- [SHA-256 校验](SHA256SUMS.txt) · [测试记录](worldbosses-0.3.3-validation.json)

**安装：** Minecraft Java 1.21.10、Fabric Loader 0.17.3 或更新版本、Java 21。退出游戏，移出旧的 World Bosses JAR，将新版与对应的 Fabric API 放入游戏的 `mods` 文件夹后重启。ZIP 已包含两个 JAR。客户端与服务器使用同一版本。

**验证：** 构建、6 项生成预算单元测试、5 项资源测试、26 项模组服务端 GameTest、正式 JAR 完整性和 Mixin 引用检查通过。新测试覆盖全部 68 种 Boss 六倍生命、真实 NBT 存档迁移、多种三倍攻击、装备减伤和受伤间隔。本次数值修改未重新进行图形客户端验证。
