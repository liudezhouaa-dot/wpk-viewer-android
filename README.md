# WPK 模型馆 · Android

安卓本地 WPK 展示与收藏应用，支持 Live2D MOC3 和 Spine 4.2 JSON。导入模型后可离线使用。

## 下载

[下载 0.3.9 APK](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.9/WPK-Viewer-0.3.9-debug.apk) · [发布页面](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/tag/v0.3.9) · [手机复测步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.9/TESTING.md)

最低 Android 8.0，建议保持 Android System WebView 更新。覆盖安装保留已有模型、分类、看板和存档。当前为 debug 测试包，尚未完成安卓真机验收。

## 0.3.9 更新

- 时装库右侧动态切换、收藏和设为看板取消文字及长按钮，与原视图／档案／区域统一为两排三列的纯图标。
- 六个按钮同为 27×27、矢量 22×22 逻辑像素，白／金色风格一致。收藏显示空心／实心爱心，动态及看板状态高亮；保留悬停提示和无障碍名称。
- 动静切换、独立模型收藏、看板分配与原点击反馈保留，原模型状态和卡片外观不变。

96 项单元、169 项桌面检查和 170 组原生解码向量通过；构建、v2 签名及 Android Lint（0 错误）通过。尚未完成安卓真机验收。

[纯图标布局](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.9/fashion-shop-initial.png)

公开预览使用生成的几何封面，未包含私有模型或用户原录屏。

## 0.3.8 更新

- 「卡片外观」只保留圆角及并列的「流光配色」「底部效果」两个紧凑按钮，底部控件收纳进独立子页。
- 底部新增「同步左／上流光」，持续跟随配色、比例、深浅、混搭、纹理、速度和方向。通过扩展同一流光层的蒙版，共用材质和动画相位，保留原封面大小，不重启模型或动画。
- 同步不覆盖原独立底部参数，切回其他模式可继续编辑；底部页恢复默认只恢复底部。左／上留边均为零时，底部仍可流动。设置自动保存，主页与时装页入口一致。

96 项单元、169 项桌面检查和 170 组原生解码向量通过；构建、v2 签名及 Android Lint（0 错误）通过。新增像素对照确认同步只改变底部，封面与原左／上区域保持一致；实际 WPK 验证同步不中断播放器和共享状态。尚未完成安卓真机验收。

[收纳后的设置](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.8/footer-sync-menu.png) · [底部同步设置](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.8/footer-sync-settings.png)

公开预览仅使用生成的几何封面，未包含私有模型或原录屏。

## 0.3.7 更新

- 时装库默认显示选中模型的静态封面。右侧收藏上方新增「切换动态／切换静态」，选新卡恢复静态；切回静态保存并释放播放器，加载期间也可取消，不重置模型互动与换装。
- 原「流光」改成统一「卡片外观」入口，使用棱角金属按钮与重画矢量图标。内层封面与外层卡框圆角各 0—18；原流光设置收纳到「流光配色」。
- 去掉选中卡底部重复名字，改为独立自定义镭射／流线／呼吸／关闭，可调整颜色、强度与速度。所有外观实时预览并自动保存，画像尺寸保持不变，未选中卡不运行底部效果。
- 隐藏右上重复品牌摘要，左上保留黄色完整模型名、品牌与标签，长名完整换行，移除下方重复角色名。

94 项单元、163 项桌面检查（含实际 WPK 静动态切换、加载取消及共享状态）和 170 组原生解码向量通过；构建、v2 签名及 Android Lint（0 错误）通过。尚未完成安卓真机验收。

[卡片外观](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.7/fashion-presentation-appearance.png) · [静态布局与长名字](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.7/fashion-presentation-static.png)

公开图片使用生成的几何封面，未包含私有模型或原录屏。

## 0.3.6 更新

- 时装库底部封面固定隐藏品牌和游戏图标，保留星级与标签；其他页面沿用原全局开关，左上模型品牌资料保留。
- 新增「设置 → 时装流光」，时装页也有同一入口。支持 2—8 色、HEX、各色比例与深浅、顺序、四种混搭、混合／纹理强度、速度和四向流动，提供配色预设和恢复默认。
- 左／上留边分别 0—40 逻辑像素，只扩大卡框与流光窗口，封面保持 85×134.5 不变。上方搜索、操作及文本选项避让扩框；实时预览与自动保存，不重载模型。

92 项单元、154 项桌面检查（含实际 WPK 播放／互动）和 170 组原生解码向量通过；构建、v2 签名及 Android Lint（0 错误）通过。尚未完成安卓真机验收。

[流光设置](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.6/foil-settings.png) · [颜色编辑](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.6/foil-colors.png) · [扩大窗口](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.6/foil-expanded.png)

公开预览仅使用生成的几何封面，未包含私有模型或原录屏。

## 0.3.5 更新

沿用已确认预览版的左／上「┏」形露底结构，按新增高清录屏继续精修：

- 柔和镭射和有机闭合等高线持续向左上流动，画像尺寸及位置固定，取消覆盖全图扫光和按压缩放。纹理子层以 16 秒周期移动，只有选中卡运行。
- 卡宽 96、间距 7、普通高 140／选中高 154、上移 21 逻辑像素，增加 2.5 像素浅圆角与低对比边线；底栏调整为冷深灰。
- 新选中先亮框、短延迟后抽出，旧卡立即回落。重复点击当前卡保持流动进度，不重载模型。系统减少动态效果时保持静态纹理。
- 标签库、含义图标、全局封面开关、点击音、真实播放／互动／存档和手势保留。

84 项单元、145 项桌面检查和 170 份 Java/Python 解码核对通过；构建、v2 签名及 Android Lint（0 错误）通过。6 项边缘专项检查包含像素相位对照、画像稳定、循环接缝、几何尺寸和减少动态效果。没有 Android 真机验收，不承诺与官方材质像素／帧级 100% 一致。

[持续动效 MP4](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.5/edge-flow-generated.mp4) · [动效 GIF](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.5/edge-flow-generated.gif) · [当前布局](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.5/refined-layout-generated.png) · [边缘专项记录](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.5/edge-verification.json)

预览是实际桌面浏览器动画，使用生成的几何封面，不是原游戏录屏或私有模型。原录屏及参考截帧不公开。

## 0.3.4 界面预览测试版

直接打包当前工作区，供先确认界面与操作效果。覆盖安装保留已有数据。

发布准备仅更新 Android 版本号及诊断版本标识，未调整界面或功能。已通过构建、Android Lint（0 错误）、v2 签名及安装包资源与当前工作区一致性检查。实现差异对比和功能审查等待用户确认效果后进行；本版未做 Android 真机测试或功能回归，不沿用 0.3.3 的测试数量。检查范围见本版 validation.json 与 TESTING.md。

## 0.3.3 更新

- 时装库按录屏重绘侧栏选中底板、金色竖条和缓慢漂移的曲线纹理；底部约 94 像素窄卡、白色选中框、上移抽出、图像放大和扫光。选卡保留列表，只切换当前动态预览。
- 新进入默认选择并显示筛选集合首个模型，从指定模型进入则自动定位。左上显示实际品牌图标、品牌名、时装和角色；品牌下显示已分配标签及含义，右侧白色图标点击显示说明。
- 新增标签库与含义图标库：独立新增／编辑名称、含义、矢量图样，标签选四种色系，可从相册选择图标。逐模型分配，删除定义先显示引用数，只解除相关标记，不删模型。
- 预置绿色新品、玫红限时标签，以及方块特殊互动、人物模型改动、手掌高级互动时装图标。由用户明确分配，不自动猜测模型功能。
- 路径：时装库 → 标记 → 标签库／含义图标库；模型归档内也可分配。定义、分配与旧数据保留，修改标记不重载播放中的模型，原品牌／游戏／星级全局开关仍独立生效。

84 项单元、139 项桌面检查和 170 份 Java/Python 解码核对通过；构建、v2 签名及 Android Lint（0 错误）通过。没有 Android 真机验收。

新增图标与纹理为 SVG／CSS 重绘，没有官方原始 UI 图集，不宣称像素级等同原素材。以下公开预览只用生成的几何封面：

[时装库](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.3/fashion-shop-initial.png) · [选中封面](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.3/fashion-shop-selected.png) · [图标说明](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.3/fashion-shop-legend.png) · [标签库](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.3/fashion-shop-labels.png) · [含义图标库](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.3/fashion-shop-icons.png)

## 0.3.2 更新

- 游戏图鉴仅显示已添加的精美游戏标签。预置交错战线、碧蓝航线、棕色尘埃2；使用纹理炫彩卡面、矢量文字和独立小徽标，保留自定义游戏和图标。
- 所有时装封面统一提供品牌、游戏、收藏星级三个独立全局开关（默认开启），即时同步并自动保存。品牌沿用下中部大水印，游戏小徽标在右上，星星更小，缺归属／0 星时不占位。
- 覆盖角色、收藏、时装横竖条、合集明细／组合封面、品牌页、单／双看板、选择小图和主页收藏小图。切换开关不重载播放中的模型，不改变模型状态或取景。
- 已有分类 ID、图标、模型归属及主动删除保留，棕色尘埃第一代不会被自动归为第二代。

78 项单元、129 项桌面检查和 170 份 Java/Python 解码核对通过；构建、v2 签名及 Android Lint（0 错误）通过。没有 Android 真机验收。

游戏标签为根据[交错战线官网](https://www.megagamelog.com/)、[碧蓝航线官网](https://game.bilibili.com/blhx/)、[棕色尘埃2官网](https://www.browndust2.com/zh-cn/)风格自行设计的 SVG，非官方原始标志；保留 Noto Sans CJK 的 SIL OFL 许可。

[游戏图鉴](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.2/gallery-games.png) · [封面标记](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.2/gallery-roles.png) · [三个全局开关](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.2/gallery-cover-settings.png)

公开预览仅用生成的几何封面，安装包不带模型。覆盖安装保留原有数据。

## 0.3.1 更新

按 8 项反馈精简入口与收藏布局：

- 顶部按当前角色实际收藏等级显示相同颗数的星星，并显示当前模型所属品牌，无品牌不显示；移除模型／品牌总数和看板数量。
- 右上删除礼物、导入 WPK、看板管理入口，保留时装库；头像进入收藏中心，资料编辑放在中心上方。
- 左侧改为两个“待实现功能”占位、我的收藏和看板；看板直接进入原看板设置，左下重复看板按钮删除。
- 设置移除动作与互动、切换背景、界面声音、打开模型库四个重复按钮；导入管理移除游戏／品牌和角色网格，外部功能仍可用。
- 精选右大卡改全角色库，删除最近加入，下方保留品牌图鉴并加入游戏图鉴。游戏分类卡显示实际角色和时装数量，可管理游戏、进入对应角色库及待归档分组。
- 我的收藏保留左侧导航，仅在右侧显示五列网格；搜索、筛选、批量管理与详情返回保留。

73 项单元、121 项桌面检查和 170 份 Java/Python 解码核对通过，构建、v2 签名及 Android Lint（0 错误）通过。渲染算法未改动，安卓真机仍需验证。

[主页布局](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.1/gallery-home.png) · [精选展台](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.1/gallery-overview.png) · [收藏布局](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.1/gallery-favorites.png) · [游戏图鉴](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.1/gallery-games.png)

以上预览使用测试生成的几何封面，不是内置模型或用户截图。覆盖安装保留原有数据。

## 0.3.0 更新

按用户参考录屏的 1280×576 有效画面重做完整主页和收藏中心：八列角色网格、真实动态档案、右侧竖向换装、底部横向时装条、推荐横卡、系列竖卡和公告。横屏等比适配，统一白／金色矢量、角标、细纹、虹彩与过渡。缺少官方 UI 图集与字体，属于按参考布局重绘，不能等同原素材像素级复制。

角色按明确的来源游戏与角色名归组，未整理文件不猜合并；支持个人收藏等级、自定义封面焦点、搜索排序、组合筛选和批量归档。预览不改变主页选择，设为看板明确选择单模型位或双模型左右，空双模型再选择另一侧。

新增多对多系列合集、静态背景库、展示预设、可编辑图文专题和真实应用记录。模型互动／换装状态跨入口共享，视角分别按页面与看板位置保存；预设保存搭配和视角，不回滚旧互动。进入动态预览释放主页单双模型渲染器，退出恢复；设置面板与文本选项不被时装卡片条遮挡。

声音库保留四套界面音效并支持本地背景音乐、独立音量与前后台控制，模型原语音独立。导入可先使用后整理，相同内容定位已有条目，同名异内容分开；删除模型先显示引用并确认，删除合集不删模型。自动待机、原触点、三连恢复 UI、独立文本／区域、模型锁定和重置、贴图与渲染分辨率分离及诊断继续保留，部件按钮保持移除。

73 项单元、113 项桌面检查、170 份 Java/Python 解码掩码核对，以及 APK 构建、v2 签名和 Android Lint（0 错误）通过。详见 [validation.json](validation.json) 和发布附件 regression.json。桌面软件 WebGL、触控模拟与原生桥接模拟不能替代手机系统选择器、WebView、音频、触控、内存和高刷性能验收。

公开布局图使用测试生成的几何封面，不是内置模型或游戏截图：

[完整主页](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.0/gallery-home.png) · [精选展台](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.0/gallery-overview.png) · [角色网格](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.0/gallery-roles.png) · [角色档案](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.0/gallery-detail.png) · [时装横条](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.0/gallery-fashion.png) · [系列卡片](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.3.0/gallery-collections.png)

## 使用

1. 覆盖安装 APK，进入上次看板；空库从收藏中心「导入管理」选择自己的文件。
2. 左下收藏卡打开角色网格，右上高跟鞋打开时装库，右上小图标打开公告；头像进入收藏中心。
3. 在「导入管理 → 归档」设置游戏、角色名、服装名与品牌。角色网格单击详情、长按管理；详情查看真实资料、换装和原互动。
4. 预览后「设为看板」选择位置返回主页。收藏中心另有合集、背景、展示预设及声音管理。

左下四快捷为隐藏 UI、文本、随机、背景；左侧「看板」打开看板设置；右下为视图、动作、档案、固定、区域与圆形设置，金色菱形收起工具。隐藏 UI 后普通轻点继续互动，三连点直接恢复；文本和区域独立。位置、缩放和模型状态自动保存，不需要保存按钮。

模型与自选媒体保存在应用私有目录。卸载或清除数据会移除库和状态；系统突然强杀或断电可能丢失最近一次定期存档之后的变化。

## 支持范围与素材

支持 STM_1_0 WPK/LPK、Live2D MOC3／motion3／physics3／网格命中与参数控制、Spine 4.2 JSON／Atlas／分层动画／骨骼命中与父子模型，以及常见变量条件、语音字幕和菜单。以两个实际 WPK 为兼容基线；STD2_0 路径已实现但没有样本验证。未覆盖全部历史格式、EX 指令和控制器，不支持旧 .moc、非 4.2 或二进制 Spine、跨类型子模型、任意 EX 脚本、动态壁纸和悬浮窗。原包缺失资源不会自动补齐，未知分支会告警。

仓库和安装包不含私有 WPK、解包模型、角色贴图、模型语音、原录屏、参考截图或用户诊断。内置 21 款品牌徽标为按用户参考追摹的矢量轮廓，权利归原权利人；公开下载不表示重新授权第三方组件或标识。许可与来源见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) 及 APK 内 assets/licenses。

## 历史版本

以下为各版本发布当时的说明，当前入口与行为以上文 0.3.0 为准。

## 0.2.14 更新

修复“固定／已固定”切换时重画图标导致的点击音遗漏：点击图标、文字或按钮空白都只播放一次，固定使用确认音，解除使用取消音。

模型画面的正常轻点也有点击音，包括原有触点和非触发区域。拖动、双指缩放、取消触摸不发声；隐藏 UI 继续可用，恢复 UI 的第三次轻点仍单独消费。单／双模型采用同一套音效与音量，双模型由主页音频上下文播放以避免重复。

「设置 → 界面声音」提供当前原版（默认）、晶透轻响、精密机芯、柔和木触四套方案，各有独立的确认／取消音，并可分别试听。原版两段 WAV 保持原样；新增三套为程序合成的短反馈。新增模型轻点音效独立开关，方案、开关和音量自动保存；模型原有语音不受界面音效设置影响。

63 项单元、138 项桌面检查，以及 APK 构建、v2 签名与 Android Lint（0 错误）通过。桌面检查验证音频解码、实际播放节点和触控路由，手机实际听感与触控仍需真机验收。

[声音设置预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.14/interface-sound-settings.png) · [手机复测步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.14/TESTING.md)

## 0.2.13 更新

移除主页及设置中的部件按钮，不再保留栏外入口。设置首页第一项为「重置当前模型」，双模型先选择左／右侧，再确认重置；移除原来的状态保存、部件与状态、暂停入口，自动保存继续工作。

设置入口改成随文字宽度排列的等高紧凑按钮，一行放多个；打开模型库改为三人像与环形箭头矢量图标。按钮新增按下缩小与高亮，松手再次显示点击标记，长按后也有反馈；关闭界面音效或系统选择减少动画时仍保留可见反馈。

60 项单元、130 项桌面检查，以及 APK 构建、v2 签名和 Android Lint（0 错误）通过。桌面触摸检查不等同于安卓真机手感验收。

[设置预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.13/compact-settings.png) · [收展预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.13/ui-rail-preview.mp4) · [手机复测步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.13/TESTING.md)

## 0.2.12 更新

按用户提供的新录屏重做右下收缩：金色菱形沿横线移动，工具按钮依次淡出，展开时反向出现；末端圆形设置保留，收起后仍可使用。快捷栏提供已有的视图、动作、部件、固定和区域功能，收起状态自动保存。

按钮使用上图标下文字、白／金色实心矢量及镂空细节，设置入口加入分层细环、断续弧线和低速微动；方形／六边形点击瞬态及设置面板图标同步调整。以录屏实际 1280×576 游戏区域等比参考大小：眼睛 38 px、小按钮 28 px、末端圆 128 px，其他视口等比缩放。原录屏、角色和其他游戏界面截图不会内置。

60 项单元、124 项桌面检查及构建、签名、Lint 通过；保留模型锁定、独立文本、双模型切换和自动保存，真机显示与手感仍待安装验证。

[动效预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.12/ui-rail-preview.mp4) · [展开预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.12/video-rail-expanded.png) · [收起预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.12/video-rail-collapsed.png) · [手机复测步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.12/TESTING.md)

## 0.2.11 更新

左下快捷图标与收藏卡、右侧按钮可分别通过边缘双箭头收起／展开，状态独立保存；收起内容不接受焦点，也不挡模型点击。时装库移到右上角，重画为金色尖头露跟细高跟矢量图标，保留细光和星芒动效。

右侧新增模型锁定：固定单指拖动、双指移动／缩放、滚轮及视图按钮，保留动画、原有点击和选项；单／双模型一致。锁定自动保存，隐藏 UI、收起控件、切换看板和重新进入后仍保持；解除后恢复原拖动模式，文本框独立手势继续可用。

60 项单元、116 项桌面检查及构建、签名、Lint 通过，安卓真机手感仍待验证。

[展开预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.11/control-shelves-expanded.png) · [收起预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.11/control-shelves-collapsed.png) · [手机测试步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.11/TESTING.md)

## 0.2.10 更新

修复开启性能浮窗时，双角色尚未加载完导致主页动画循环中断、切回单角色停住的问题；延迟加载期间允许状态暂缺，辅助状态工作不再终止帧循环。主动保存的暂停状态仍保留。

「设置 → 状态保存 → 重置当前模型状态」恢复初始换装、参数、互动、子模型、姿态与视角并重新播放。双角色只重置所选一侧；保留模型文件、看板、分类、背景、语言及文本外观和位置。新状态自动保存，旧异步存档不能覆盖重置结果。

隐藏主页 UI 不再隐藏文本和选项，独立文本开关始终生效，三连点恢复不会改写其状态。59 项单元、110 项桌面检查及编译、签名、Lint 通过，安卓真机效果仍待安装验证。

[重置入口预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.10/model-reset-settings.png) · [手机复测步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.10/TESTING.md)

## 0.2.9 更新

设置 → 文本显示新增游戏面板、磨砂面板、纯文字样式，以及 0～100% 背景不透明度。文字与原有选项保持清晰；文本框内双指缩放和移动（60%～200%），按目标字号重新排版。把手拖动和长文本单指滑动继续可用。外观、位置与缩放自动保存，支持单／双模型，兼容旧设置。

59 项单元、103 项桌面检查及构建、签名、Lint 通过。浏览器真实双指输入已验证，手机触控手感仍待安装验证。

[文本设置预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.9/text-panel-settings.png) · [手机测试步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.9/TESTING.md)

## 0.2.8 更新

修复隐藏 UI 时普通模型点击被拦截的问题，单／双模型的 Spine、Live2D 均继续按原包条件互动。三连点恢复 UI，前两次是普通轻点，第三次只用于恢复，不额外触发动作。拖动、双指缩放与区域独立显示保留。

56 项单元、96 项桌面检查及编译、签名、Lint 通过；新增隐藏 UI 下真实动作、菜单、手势及双模型回归，安卓触控仍待真机验证。

## 0.2.7 更新

针对真机反馈中的渲染提交与周期存档耗时，提前跳过可安全省略的全透明 Spine 槽位，保留微透明细节、特殊混合与裁剪终点。本地样本跳过 221／477 个槽位，原路径与优化路径逐像素一致；这属于桌面工作量验证，不是手机 FPS 提升比例。

Spine 姿态使用紧凑数值记录，避免重复遍历运行时骨骼图；周期 JSON 编码移至工作线程，操作和生命周期检查点继续保存。通过序号防止旧异步结果覆盖较新状态；兼容旧检查点，工作线程失败时回退。诊断新增透明槽位计数、draw calls 与存档捕获／编码／写入分项。

56 项单元、91 项桌面检查及编译、签名、Lint 通过，0.2.7 手机效果仍需复测。请保持原图贴图、85% 渲染，分别测试 60／120 帧。

[手机复测步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.7/TESTING.md) · [绘制与存档验证](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.7/spine-optimization.json)

## 0.2.6 更新

“帧率与画质”拆分贴图清晰度（原图／2048／1024）与渲染分辨率（100%／85%／65%）。默认原图＋85%，85% 约为原生 72% 像素量；降低渲染分辨率保留原图贴图，不重新上传纹理、重启动作或改变点击坐标。旧版帧率及贴图选择继承，可点击“高清流畅基准：原图＋85%＋60 帧”开始对照。

新增性能浮窗、帧间隔与 CPU/GPU 分项耗时、长帧统计，安卓端原生 VSync 与窗口 FrameMetrics。GPU 计时不可用时明确标注，CPU 提交与 GPU 完成区分。报告带有界帧时间序列，可复制或选择位置保存，不会自动上传，也不包含私有模型标识或素材。

51 项单元和 86 项桌面检查、编译、签名及 Lint 通过；尚未完成 K60 Ultra 真机验收，不能保证任意模型达到高清 120 帧。

[手机测试步骤](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.6/TESTING.md) · [性能设置预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.6/performance-panel.png)

## 0.2.5 更新

修正轻微刷新抖动导致的额外跳帧，保留连续时间基准；按钮按下即时反馈、缩放／透明度过渡及菜单滑入，减少图标滤镜与背景模糊重绘。菜单和暂停继续保持所选刷新偏好，后台释放。

时装库完全覆盖模型时跳过不可见的 GPU 绘制，动作和记录继续；Spine 查询、排序及采样轨道复用减少重复工作，操作保存安排到空闲时段，离开及后台仍立即保存。区域辅助画布最高 60 Hz，实际命中使用当前骨骼，模型档位仍为 60／90／120。

44 项单元和 78 项桌面检查、编译、签名及 Lint 通过。±0.6 毫秒回调抖动测试中，旧调度为约 43.8／65.6／87.5 帧，新调度为 60／90／120；这只是算法复现，并非手机实测。安卓真机帧率仍待验证。

## 0.2.4 更新

修正 0.2.3 点击音裁切过短的问题：从新录屏保留 460 毫秒点击／确认片段，独立加入 630 毫秒取消／返回片段，保留完整尾音。打开、选择、确认与返回、关闭、取消使用不同声音；设置 → 界面声音可分别试听，开关和音量继续自动保存，模型语音不受影响。未完成手机实际试听。

衣架改为右下方的金色高跟鞋“时装库”，带渐变、细光、三层星芒和轻抬反馈，支持减少动态效果偏好，且不遮挡区域／设置。左下角恢复五个紧凑图标。

20 款小截图徽标重建曲线，21 款内置品牌直接以 SVG 节点绘制，去掉模糊光晕，在高像素密度屏幕上保持矢量边缘，不受模型贴图画质档位限制。优化不能凭空恢复源截图已经缺失的极细节；自定义图标和已有分类保留。

[时装库入口预览](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.4/fashion-entry.png) · [21 款品牌矢量图包](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.4/brand-vector-icons.zip)

42 项单元、72 项桌面检查及编译、签名、Lint 检查通过。新增检查覆盖两类原片段及其尾音、操作路由、独立试听与静音、右下位置和动效偏好、3 倍像素密度下的内联矢量显示。

## 0.2.3 更新

参考录屏重做品牌浏览：点击品牌进入左侧固定品牌徽标、右侧纵向服装／模型封面的页面，返回保留原列表滚动位置。“加入模型”可从本机库中多选归类，点击服装封面打开模型；品牌修改通过明确的管理／编辑入口操作。调整切换、按压反馈、六边形点击标记、细长滚动条和底部渐隐，页面切换保留背景。

设置 → 界面声音提供点击音开关、音量和试听，自动保存；关闭即停止界面声音，不改变模型原有语音和互动音效。点击音来自用户提供录屏：对齐 20 次相同瞬态以减弱背景音乐，保留 63 毫秒短音，不分发原视频或完整音轨，也不宣称等同官方原始无混音音效。

42 项单元和 66 项桌面检查通过，APK 编译、签名与 Lint 通过。桌面检查验证实际音频解码和播放节点、开关保存与后台停止；手机外放／耳机听感和真机性能仍待验收。

## 0.2.2 更新

左下角普通图标从 40 缩为 28 CSS 像素，眼睛从 46 缩为 32，收藏卡收紧为 220×48。右下角区域与设置按钮、设置内部工具和动作选项统一为深色方框、角标和白色线形图标；开启区域使用金色标记。

隐藏 UI 后连续轻点三次直接恢复 UI，无须返回按钮，恢复那次点击不执行模型互动。已开启的触发区域独立显示，隐藏和恢复 UI 均不会关闭它；再次点击区域按钮才关闭。单模型、双模型行为一致。

主页左下角新增衣架图标“品牌服装”。图鉴默认可下滑查看全部 21 款品牌，支持触摸滑动和滚轮，仍可选择“翻页浏览”，浏览方式自动保存。40 项单元、60 项桌面检查以及编译、签名、Lint 检查通过；真机触控与物理显示尺寸仍待设备验收。

## 0.2.1 更新

品牌图鉴预置按用户参考图追摹的 21 款 SVG 徽标，保留图案、英文花体与装饰细节。五列双排、每页十张卡片，提供双层卡框、角标、底部金线与品牌名称；卡片背景重建细密横纹、颗粒、等高线和低饱和炫彩反光。图标轮廓来自截图，不能等同原始高清设计稿。

整体调整导航图标、面板、按钮、半色调细节、字体字重及看板间距；左下角收藏卡加入模型封面。模型库 → 分类管理 → 服装品牌进入图鉴，点击卡片编辑名称／图标，也可新建品牌；筛选中的“浏览品牌图鉴”可直接选择品牌。升级一次性补齐内置品牌，保留自定义 ID、图标与模型归属，并记住后续主动移除的品牌。

[品牌页一](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.1/brand-gallery-1.png) · [品牌页二](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.1/brand-gallery-2.png) · [品牌页三](https://github.com/liudezhouaa-dot/wpk-viewer-android/releases/download/v0.2.1/brand-gallery-3.png)

39 项单元和 60 项桌面检查通过，安卓真机仍待验收。品牌图形权利归原权利人，来源说明见 [第三方与视觉来源声明](THIRD_PARTY_NOTICES.md)。

## 0.2.0 更新

默认横屏、沉浸全屏进入上次看板。主页参考交错战线的布局，使用自绘 SVG 图标和深色半透明面板；省略账号、资源栏与出击区域，不附带游戏图片。左下角依次为隐藏 UI、文本开关、看板设置、随机切换、相册背景。隐藏后连续轻点三次只显示左上角返回按钮，点击恢复界面。

提供五个单模型看板和一个双模型看板，支持 Spine 与 Live2D 同时播放、独立拖动缩放与自动保存；设置中可选左／右模型调整视图、动作及部件。支持随机池及每天／每次启动／返回主页轮换。背景可从相册设置，默认黑色。

模型库可搜索、排序并组合筛选游戏名与服装品牌。分类管理可添加、重命名游戏和品牌、设置品牌图标；卡片右下角“⋯”编辑所属分类。看板、背景、图标与分类均自动保存在本机；保留既有点击交互、换装、待机、现场恢复和帧率／画质选项。旧版升级后先选择一次模型，之后会记住上次看板。

本版 37 项单元与 54 项桌面检查通过。安卓横屏、系统相册、沉浸全屏及双模型内存和高刷表现尚待真机验收。

## 0.1.7 更新

齿轮 → 帧率与画质：可选 60／90／120 帧目标，以及流畅／均衡／高清。流畅将贴图最长边限制为 1024、渲染精度约原生 65%；均衡为 2048、约 85%；高清保留原图和原生精度，均受设备 GPU 上限约束。显示实际渲染 FPS、屏幕刷新率、画布与贴图尺寸，选项自动保存。

切换画质保留动作、换装、子模型和点击范围；Live2D 遮罩层精度同步调整。安卓端请求适合所选档位的同分辨率刷新模式，进入后台或离开播放页时释放偏好；逐帧更新按实际时间执行，不会因提高档位而加快动作。播放中的状态保存优先安排到空闲时段。

实际帧率受屏幕、系统策略、WebView、GPU 和模型复杂度限制，选择 120 不代表设备一定达到 120。高刷真机尚未验收；新增桌面检查模拟原生刷新桥接，仅验证请求和选项行为。平台依据：[Android 显示模式偏好](https://developer.android.com/reference/android/view/WindowManager.LayoutParams#preferredDisplayModeId)。

本版累计 32 项单元与 46 项桌面检查通过。

## 0.1.6 更新

自动保存升级为现场恢复，并移除手动保存按钮。操作后自动记录，播放中每半秒更新，返回模型馆或进入后台时立即保存。再次打开同一模型，恢复上次的动作进度、姿态及播放／暂停状态；播放中的模型继续原动作，暂停的模型保持原画面。

入场和有限点击动作保留剩余时长，恢复时不重复执行开始时的变量修改或初始化。换装、子模型、参数过渡、视角、文本等一并保留，历史音频不会自动重播。旧版状态继续兼容，旧版未记录的动作进度无法追溯。正常离开立即保存；突然强杀或断电可能丢失最后一次定期记录之后的变化。

新增 2 项单元与 5 项实际模型现场恢复检查通过，全程不点击保存按钮。累计 27 项单元与 41 项桌面检查通过，安卓真机仍待验收。

## 0.1.5 更新

齿轮新增“文本显示”“触发区域样式”“状态保存”。文本和选项可显示／隐藏，调整字号与宽度，拖动文本框上方把手移动位置。区域框可设置描边／填充／虚线、颜色、粗细、整体及填充透明度、名称显隐和字号；实际点击范围保持原包定义。

按模型自动保存换装等变量、参数锁定、区域启用状态、循环控制、皮肤、子模型与循环动作，以及视角、文本位置、背景和语言。返回模型馆、进入后台或播放中定期保存，也可手动立即保存。重新打开恢复状态并继续循环动作／待机，不续播未完成的点击动作、字幕、菜单和音频。显示样式作为应用设置保存，覆盖安装保留；卸载或清除应用数据会移除。兼容读取旧版变量，旧版未记录的完整状态无法追溯。

新增 5 项单元检查和 6 项实际模型显示／保存恢复检查通过，累计 25 项单元与 36 项桌面检查通过，尚未完成安卓真机验收。

## 0.1.4 更新

播放页移除顶部栏、底部工具栏和“轻触角色…”提示，只保留右下角的“区域”按钮与其右侧齿轮。“区域”点击显示、再次点击关闭；设置集中提供视图、暂停、动作、部件、背景、运行信息、语言和返回模型馆。

默认单指拖动模型，轻点仍执行原互动，双指可缩放和移动；暂停时也能调整画面。在设置里关闭“单指拖动模型”可使用模型原有的拖拽参数交互，开关状态自动保存。新增 6 项桌面播放页与手势检查通过，包含触摸模拟、拖动不误触、暂停画面重绘、设置导航及原生拖拽切换，仍待安卓真机验收。

## 0.1.3 更新

新增点击触发区域显示：点击顶部“区域”按钮或开启“视图 → 显示触发区域”。亮色实线表示启用区域，灰色虚线表示当前禁用区域；显示区域名称，跟随动画、缩放移动和父子模型变化，自动保存开关状态。动作继续遵循原包的状态条件和点击优先级。

新增 6 项桌面区域显示检查通过，核对 80 个 Live2D 区域及 7 个 Spine 主模型区域的中心和边界内外命中，并覆盖点击透传、视角、子模型及开关保存。尚未完成安卓真机验收；Spine 区域单位仍沿用现有兼容换算，尚未与原 EX 软件逐区比较。

## 0.1.2 更新

模型打开后自动待机，入场动作结束后自动切换，点击动作结束后恢复待机。清理停在最后一帧的高层动作，保持待机可打断，并按衣装等状态选择待机。新增 4 项实际模型自动待机检查通过，仍未进行安卓真机验收。

## 0.1.1 更新

修正可见区域取景及异常大网格导致的画面缩小；限制 Live2D 画布外遮罩，使用设备支持的高精度 Spine 贴图坐标和实际屏幕像素倍率。底部“视图”可选择适应画面、填满屏幕、全景及放大／缩小。新增 4 项渲染回归检查通过，尚未进行安卓真机验收。

