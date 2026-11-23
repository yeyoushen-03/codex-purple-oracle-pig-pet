# 紫曜小猪 · Codex 自定义桌面宠物

紫色魔法帽、白色羽翼与金色弓箭的小猪角色，沿用柔和的 3D 玩具质感、紫罗兰衣料与暖粉肤色。本仓库发布适配 Codex V2 的非官方自定义桌宠素材包，包含9组状态动作和16个注视方向。

素材包版本 **v2.1.2**；`spriteVersionNumber: 2` 表示素材格式版本。项目标注见 [project-info.json](project-info.json)。

<p align="center">
  <img src="assets/previews/idle.webp" width="192" height="208" alt="紫曜小猪待机" />
  <img src="assets/previews/running-left.webp" width="192" height="208" alt="紫曜小猪分层左跑" />
  <img src="assets/previews/running-right.webp" width="192" height="208" alt="紫曜小猪分层右跑" />
  <img src="assets/previews/look-loop.webp" width="192" height="208" alt="紫曜小猪视线方向" />
</p>

## 安装

1. 在 [Releases](https://github.com/yeyoushen-03/codex-purple-oracle-pig-pet/releases/latest) 下载 `purple-oracle-pig-v2.zip` 并解压。
2. 将整个 `purple-oracle-pig` 文件夹放入 Codex 的 `pets` 目录，确保 `pet.json` 和 `spritesheet.webp` 位于同一层。

   | 系统 | 默认位置 |
   | --- | --- |
   | macOS / Linux | `~/.codex/pets/purple-oracle-pig/` |
   | Windows | `%USERPROFILE%\.codex\pets\purple-oracle-pig\` |

   如果设置了 `CODEX_HOME`，使用该目录下的 `pets/purple-oracle-pig/`。
3. 在支持自定义 V2 宠物的 Codex 桌面版中选择「紫曜小猪」。如未刷新，重新打开宠物列表或重启客户端。

已有安装可用新包中的同名文件覆盖。

## 动作与方向

| 状态 | 帧数 |
| --- | ---: |
| 待机 | 6 |
| 向右移动 / 向左移动 | 各8 |
| 打招呼 | 4 |
| 跳跃 | 5 |
| 出错反应 | 8 |
| 等待确认 / 工作中 / 检查结果 | 各6 |

16个注视方向按22.5°标注顺时针排列，画面表现为近似方向：0°向上、90°向右、180°向下、270°向左；默认正面姿势另存。动作触发、播放和方向选择由客户端控制。

## 规格

无损透明 WebP；1536×2288；8列×11行；每格192×208；`spriteVersionNumber: 2`。

素材基于用户提供的角色参考，由 AI 辅助生成和整理。未另行授予素材的商用或再许可权利。

## 验收与已知差异

v2.1.2 将向左、向右移动各8帧改为分层腿部动画：固定圆润头脸和躯干比例，两腿交替前后摆动，保留左跑左侧握弓、右侧拉弦的关系及帽子不对称细节。采用用户确认的短步幅效果。其余9行、16方向视线和独立正面姿势逐像素保持不变。

最终图集V2验证、无损像素与其他行一致性检查通过；预览每帧100毫秒、无额外末帧停顿，原生尺寸浅深底及桌面/窄屏浏览器显示检查通过。用户已确认同步预览。少量裤脚边缘仍有1–2像素尖角；分层动作没有保证锁脚。

少数斜向变化较小，两行交界转头幅度略大；原生客户端显示未验证。详见[验收记录](docs/qa/verification.json)。

## 作者与交流

作者：[yeyoushen-03](https://github.com/yeyoushen-03)

欢迎技术交流

<img src="assets/contact/wechat-qr.png" width="240" alt="微信交流二维码" />
