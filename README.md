# English Learning Content Generation Prompts

## Directory Structure

```
english_learning/
├── prompts/                        # System prompts and templates
│   ├── system_movie_all_level.md   # Main system prompt with all levels
│   ├── system_general.jinja        # General system prompt template
│   ├── system_original.jinja       # Original system prompt
│   ├── system_slang_level2.jinja   # Level 2 slang system prompt
│   └── examples/                   # Level-specific examples
│       ├── level1_movie_examples.jinja
│       ├── level2_movie_examples.jinja
│       ├── level3_movie_examples.jinja
│       ├── level4_movie_examples.jinja
│       └── level5_movie_examples.jinja
├── outputs/                        # Generated content
│   ├── 蝴蝶效应.md
│   └── 阿甘正传.md
└── example_corpus/                 # Reference materials
    ├── 坠.md
    ├── 盗梦空间.md
    └── 喜宴.md
```