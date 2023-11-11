经济：时事、经济书籍
艺术：西方艺术史
科学：科普
哲学：宗教，一休儿博客
文学：大号诗歌、历史
生活：日常感悟，生活琐事

## Supported Front Matter

<details>
  <summary>Click to expand!</summary>


| Name                                        | Description                                                  | Notes                                                        |
| ------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| title                                       | \*                                                           | string                                                       |
| linkTitle                                   | \*                                                           | string                                                       |
| subtitle                                    | displayed below the title                                    | string, Markdown supported                                   |
| date                                        | \*                                                           | string                                                       |
| lastmod                                     | \*                                                           | string                                                       |
| publishDate                                 | \*                                                           | string                                                       |
| expiryDate                                  | \*                                                           | string                                                       |
| `<taxonomies>` eg: categories, tags, series | \*                                                           | array                                                        |
| description                                 | \*                                                           | string, Markdown supported                                   |
| summary                                     | \*                                                           | string, Markdown supported                                   |
| images                                      | \*                                                           | array                                                        |
| slug                                        | \*                                                           | string                                                       |
| url                                         | \*                                                           | string                                                       |
| draft                                       | \*                                                           | boolean                                                      |
| isCJKLanguage                               | \*                                                           | boolean                                                      |
| weight                                      | \*                                                           | integer                                                      |
| type                                        | \*                                                           | string, if equal to "poetry", will use a special layout for it |
| layout                                      | \*                                                           | string                                                       |
| outputs                                     | \*                                                           | array                                                        |
| aliases                                     | \*                                                           | array                                                        |
| markup                                      | \*                                                           | string                                                       |
| hideInHomepage                              | hide this post in homepage posts list                        | boolean, valid for "posts" homepage with `enableHideInHomepage` enabled |
| languageCode                                | add `lang` attribute with this value to `<article>`          | string                                                       |
| meta                                        | set `false` to disable post-meta                             | boolean, override `enablePostMeta` in `config.toml`          |
| displayPublishedDate                        | display published date in post-meta                          | boolean, override `displayPublishedDate` in `config.toml`    |
| displayModifiedDate                         | display modified date in post-meta                           | boolean, override `displayModifiedDate` in `config.toml`     |
| displayExpiryDate                           | display expiry date in post-meta                             | boolean, override `displayExpiryDate` in `config.toml`       |
| displayCategory                             | display category in post-meta                                | boolean, override `displayCategory` in `config.toml`         |
| displayWordCount                            | display word count in post-meta                              | boolean, override `displayWordCount` in `config.toml`        |
| displayReadingTime                          | display reading time in post-meta                            | boolean, override `displayReadingTime` in `config.toml`      |
| displayBusuanziPagePV                       | display page views in post-meta                              | boolean, override `displayBusuanziPagePV` in `config.toml`   |
| toc                                         | display TOC                                                  | boolean, override `enableTOC` in `config.toml`               |
| tocNum                                      | display TOC number                                           | boolean, override `displayTOCNum` in `config.toml`           |
| anchor                                      | enable headings anchor                                       | boolean, override `enableHeadingsAnchor` in `config.toml`    |
| displayCopyright                            | display post-copyright                                       | boolean, override `displayPostCopyright` in `config.toml`    |
| badge                                       | display updated-badge                                        | boolean, override `displayUpdatedBadge` in `config.toml`     |
| gitinfo                                     | display post-gitinfo                                         | boolean, override `displayPostGitInfo` in `config.toml`      |
| share                                       | display post-share                                           | boolean, override `displayPostShare` in `config.toml`        |
| related                                     | display related-posts                                        | boolean, override `displayRelatedPosts` in `config.toml`     |
| katex                                       | add KaTeX support                                            | boolean, override `enableKaTeX` in `config.toml`             |
| mathjax                                     | add MathJax support                                          | boolean, override `enableMathJax` in `config.toml`           |
| mermaid                                     | add Mermaid support                                          | boolean, override `enableMermaid` in `config.toml`           |
| comments                                    | set `false` to disable comments in mainSections or set `true` to enable comments in non-mainSections | boolean                                                      |
| smallCaps                                   | small caps?                                                  | boolean, override `enableSmallCaps` in `config.toml`         |
| dropCap                                     | drop cap?                                                    | boolean, override `enableDropCap` in `config.toml`           |
| dropCapAfterHr                              | drop cap after every horizontal rule tag?                    | boolean, override `enableDropCapAfterHr` in `config.toml`    |
| deleteHrBeforeDropCap                       | delete horizontal rule tag before drop cap?                  | boolean, override `deleteHrBeforeDropCap` in `config.toml`   |
| indent                                      | indent instead of margin?                                    | boolean, override `paragraphStyle` in `config.toml`          |
| indentFirstParagraph                        | indent the first paragraph?                                  | boolean, override `indentFirstParagraph` in `config.toml`    |
| align                                       | normal, justify, center                                      | string, if equal to "normal", will override `enableJustify` in `config.toml` |
| original                                    | original? You can add the following 8 terms if you set `false`. The `author` is required, other optional | boolean, override `original` in `config.toml`                |
| author                                      | author of original post                                      | string                                                       |
| link                                        | link of original post                                        | string, URL                                                  |
| copyright                                   | license of the post                                          | string, Markdown supported                                   |
| website                                     | author’s website                                             | string                                                       |
| email                                       | author’s email                                               | string                                                       |
| motto                                       | author’s description                                         | string                                                       |
| avatar                                      | author’s avatar                                              | string, URL                                                  |
| twitter                                     | author’s twitter id                                          | string                                                       |
| disqus_url                                  | \*                                                           | string, if not set, will use `Permalink` as default          |
| disqus_identifier                           | \*                                                           | string, if not set, will use `RelPermalink` as default       |
| disqus_title                                | \*                                                           | string, if not set, will use `Title` as default              |

  \*: see https://gohugo.io/content-management/front-matter/  
      and https://gohugo.io/templates/internal/#configure-disqus
</details>