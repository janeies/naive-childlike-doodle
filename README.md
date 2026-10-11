# Naive Childlike Doodle Skill

一个用于生成或编辑“拙趣儿童手绘感”位图插画的 Codex Skill。

它强调不平直的黑色手绘线条、简化造型、克制配色、灰色网点和宽松留白，适用于人物、动物、场景、产品重绘、局部风格统一及透明背景素材。

## 主要能力

- 从文字描述生成新的拙趣手绘插画
- 按参考图保留角色身份、姿势、表情和标志性配件
- 简化复杂场景，减少建筑和背景细节
- 对指定区域进行局部风格修正
- 输出补齐遮挡部分的透明背景 PNG 素材
- 检查并修正线条过直、细节过密、颜色过艳、角色悬浮等常见问题

## 安装

将整个仓库复制或克隆到 Codex Skills 目录：

```text
$CODEX_HOME/skills/naive-childlike-doodle
```

重新打开 Codex 后即可调用：

```text
$naive-childlike-doodle
```

## 使用示例

```text
$naive-childlike-doodle 把这张照片重绘成拙趣儿童手绘插画，
保留人物姿势和表情，线条不要太直，减少背景细节，
使用灰色网点和两种低饱和强调色。
```

```text
$naive-childlike-doodle 把这个产品画成儿童拙趣简笔画，
补齐被遮挡的部分，输出透明背景 PNG。
```

## 默认视觉语言

- 暖白色纸张背景和近黑色墨线
- 轻微歪斜、粗细不均、连接不完美的轮廓
- 保留主体识别特征，删除非必要小细节
- 灰色网点只用于结构、材质和阴影
- 默认最多使用两种低饱和强调色
- 避免光滑矢量感、照片写实、渐变和高光 3D 质感

## 文件结构

```text
SKILL.md
references/
  style-system.md
  prompt-recipes.md
```

`SKILL.md` 包含核心工作流程和质量检查；`references` 中提供详细画风规则与提示词结构。

