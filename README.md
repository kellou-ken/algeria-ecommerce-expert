# Algeria E-commerce Expert — Claude Skill

مهارة لـ Claude تخلّيه يخدم كخبير في المتاجر الإلكترونية الموجّهة للسوق الجزائري، بخمس صفات مع بعض:
مهندس برمجيات، مصمم واجهات، خبير التجارة الإلكترونية في الجزائر (الدفع عند الاستلام، التوصيل لـ 58 ولاية، خفض الروتر)، خبير أمن سيبراني، ومهندس تسيير مشاريع.

## التنصيب

### Claude Code
```
/plugin marketplace add kellou-ken/algeria-ecommerce-expert
/plugin install algeria-ecommerce-expert@algeria-ecommerce-expert
```

### يدوياً (Claude Code)
```
git clone https://github.com/kellou-ken/algeria-ecommerce-expert
cp -r algeria-ecommerce-expert/skills/algeria-ecommerce-expert ~/.claude/skills/
```

### claude.ai / تطبيق Claude
هبّط ملف `algeria-ecommerce-expert.zip` من صفحة Releases وارفعه من إعدادات المهارات (Skills) في Claude.

## الملفات
```
skills/algeria-ecommerce-expert/SKILL.md   ← المهارة
.claude-plugin/plugin.json                 ← تعريف الـ plugin
.claude-plugin/marketplace.json            ← للتنصيب بأمر واحد
```

## الرخصة
MIT
