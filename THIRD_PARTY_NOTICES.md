# Third-Party Notices

DeepChat（深聊）自有代码为闭源软件，版权归其作者所有，本文件不构成对 DeepChat 本身的开源许可。以下列出随应用分发的第三方组件及其许可证原文。

- 应用版本：0.2.1
- 生成日期：2026-11-18
- 生成方式：`npm run licenses`（扫描构建产物、Gradle releaseRuntimeClasspath 与 SwiftPM 清单）

## 概览

- Web 运行时组件：84
- Android 运行时组件：52
- iOS 组件：3
- 已核实许可证文件：139
- 仅有包元数据（未附带许可证文件）：0
- 待人工确认：0

## Web 运行时（打包进应用）

| 组件 | 版本 | 许可证 | 来源 | 状态 |
| --- | --- | --- | --- | --- |
| @capacitor/core | 8.6.2 | MIT | https://github.com/ionic-team/capacitor | 已核实 |
| @ungap/structured-clone | 1.4.0 | ISC | https://github.com/ungap/structured-clone | 已核实 |
| bail | 2.0.2 | MIT | https://github.com/wooorm/bail | 已核实 |
| capacitor-secure-storage-plugin | 0.14.2 | MIT | https://github.com/martinkasa/capacitor-secure-storage-plugin | 已核实 |
| ccount | 2.0.1 | MIT | https://github.com/wooorm/ccount | 已核实 |
| comma-separated-tokens | 2.0.3 | MIT | https://github.com/wooorm/comma-separated-tokens | 已核实 |
| cookie | 1.1.1 | MIT | https://github.com/jshttp/cookie | 已核实 |
| decode-named-character-reference | 1.3.0 | MIT | https://github.com/wooorm/decode-named-character-reference | 已核实 |
| devlop | 1.1.0 | MIT | https://github.com/wooorm/devlop | 已核实 |
| escape-string-regexp | 5.0.0 | MIT | https://github.com/sindresorhus/escape-string-regexp | 已核实 |
| estree-util-is-identifier-name | 3.0.0 | MIT | https://github.com/syntax-tree/estree-util-is-identifier-name | 已核实 |
| extend | 3.0.2 | MIT | https://github.com/justmoon/node-extend | 已核实 |
| hast-util-to-jsx-runtime | 2.3.7 | MIT | https://github.com/syntax-tree/hast-util-to-jsx-runtime | 已核实 |
| hast-util-whitespace | 3.0.0 | MIT | https://github.com/syntax-tree/hast-util-whitespace | 已核实 |
| html-url-attributes | 3.0.1 | MIT | https://github.com/rehypejs/rehype-minify/tree/main/packages/html-url-attributes | 已核实 |
| inline-style-parser | 0.2.9 | MIT | https://github.com/remarkablemark/inline-style-parser | 已核实 |
| is-plain-obj | 4.1.0 | MIT | https://github.com/sindresorhus/is-plain-obj | 已核实 |
| longest-streak | 3.1.0 | MIT | https://github.com/wooorm/longest-streak | 已核实 |
| lucide-react | 1.74.0 | ISC | https://github.com/lucide-icons/lucide | 已核实 |
| markdown-table | 3.1.0 | MIT | https://github.com/wooorm/markdown-table | 已核实 |
| mdast-util-find-and-replace | 3.0.4 | MIT | https://github.com/syntax-tree/mdast-util-find-and-replace | 已核实 |
| mdast-util-from-markdown | 2.1.0 | MIT | https://github.com/syntax-tree/mdast-util-from-markdown | 已核实 |
| mdast-util-gfm | 3.1.0 | MIT | https://github.com/syntax-tree/mdast-util-gfm | 已核实 |
| mdast-util-gfm-autolink-literal | 2.1.0 | MIT | https://github.com/syntax-tree/mdast-util-gfm-autolink-literal | 已核实 |
| mdast-util-gfm-footnote | 2.1.0 | MIT | https://github.com/syntax-tree/mdast-util-gfm-footnote | 已核实 |
| mdast-util-gfm-strikethrough | 2.0.1 | MIT | https://github.com/syntax-tree/mdast-util-gfm-strikethrough | 已核实 |
| mdast-util-gfm-table | 2.0.1 | MIT | https://github.com/syntax-tree/mdast-util-gfm-table | 已核实 |
| mdast-util-gfm-task-list-item | 2.0.1 | MIT | https://github.com/syntax-tree/mdast-util-gfm-task-list-item | 已核实 |
| mdast-util-phrasing | 4.1.0 | MIT | https://github.com/syntax-tree/mdast-util-phrasing | 已核实 |
| mdast-util-to-hast | 13.2.2 | MIT | https://github.com/syntax-tree/mdast-util-to-hast | 已核实 |
| mdast-util-to-markdown | 2.2.3 | MIT | https://github.com/syntax-tree/mdast-util-to-markdown | 已核实 |
| mdast-util-to-string | 4.0.0 | MIT | https://github.com/syntax-tree/mdast-util-to-string | 已核实 |
| micromark | 4.0.3 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark | 已核实 |
| micromark-core-commonmark | 2.0.4 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-core-commonmark | 已核实 |
| micromark-extension-gfm | 3.0.0 | MIT | https://github.com/micromark/micromark-extension-gfm | 已核实 |
| micromark-extension-gfm-autolink-literal | 2.1.0 | MIT | https://github.com/micromark/micromark-extension-gfm-autolink-literal | 已核实 |
| micromark-extension-gfm-footnote | 2.1.0 | MIT | https://github.com/micromark/micromark-extension-gfm-footnote | 已核实 |
| micromark-extension-gfm-strikethrough | 2.1.0 | MIT | https://github.com/micromark/micromark-extension-gfm-strikethrough | 已核实 |
| micromark-extension-gfm-table | 2.1.2 | MIT | https://github.com/micromark/micromark-extension-gfm-table | 已核实 |
| micromark-extension-gfm-tagfilter | 2.0.0 | MIT | https://github.com/micromark/micromark-extension-gfm-tagfilter | 已核实 |
| micromark-extension-gfm-task-list-item | 2.1.0 | MIT | https://github.com/micromark/micromark-extension-gfm-task-list-item | 已核实 |
| micromark-factory-destination | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-factory-destination | 已核实 |
| micromark-factory-label | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-factory-label | 已核实 |
| micromark-factory-space | 2.1.0 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-factory-space | 已核实 |
| micromark-factory-title | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-factory-title | 已核实 |
| micromark-factory-whitespace | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-factory-whitespace | 已核实 |
| micromark-util-character | 2.1.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-character | 已核实 |
| micromark-util-chunked | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-chunked | 已核实 |
| micromark-util-classify-character | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-classify-character | 已核实 |
| micromark-util-combine-extensions | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-combine-extensions | 已核实 |
| micromark-util-decode-numeric-character-reference | 2.0.2 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-decode-numeric-character-reference | 已核实 |
| micromark-util-decode-string | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-decode-string | 已核实 |
| micromark-util-edit-map | 1.0.0 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-edit-map | 已核实 |
| micromark-util-encode | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-encode | 已核实 |
| micromark-util-html-tag-name | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-html-tag-name | 已核实 |
| micromark-util-normalize-identifier | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-normalize-identifier | 已核实 |
| micromark-util-resolve-all | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-resolve-all | 已核实 |
| micromark-util-sanitize-uri | 2.0.1 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-sanitize-uri | 已核实 |
| micromark-util-subtokenize | 2.1.0 | MIT | https://github.com/micromark/micromark/tree/main/packages/micromark-util-subtokenize | 已核实 |
| property-information | 7.2.0 | MIT | https://github.com/wooorm/property-information | 已核实 |
| react | 19.3.1 | MIT | https://github.com/react/react | 已核实 |
| react-dom | 19.3.1 | MIT | https://github.com/react/react | 已核实 |
| react-markdown | 10.1.0 | MIT | https://github.com/remarkjs/react-markdown | 已核实 |
| react-router | 7.18.5 | MIT | https://github.com/remix-run/react-router | 已核实 |
| react-router-dom | 7.18.5 | MIT | https://github.com/remix-run/react-router | 已核实 |
| remark-gfm | 4.0.1 | MIT | https://github.com/remarkjs/remark-gfm | 已核实 |
| remark-parse | 11.0.0 | MIT | https://github.com/remarkjs/remark/tree/main/packages/remark-parse | 已核实 |
| remark-rehype | 11.1.2 | MIT | https://github.com/remarkjs/remark-rehype | 已核实 |
| scheduler | 0.28.0 | MIT | https://github.com/react/react | 已核实 |
| set-cookie-parser | 2.7.3 | MIT | https://github.com/nfriedly/set-cookie-parser | 已核实 |
| space-separated-tokens | 2.0.2 | MIT | https://github.com/wooorm/space-separated-tokens | 已核实 |
| style-to-object | 2.0.2 | MIT | https://github.com/remarkablemark/style-to-object | 已核实 |
| trim-lines | 3.0.1 | MIT | https://github.com/wooorm/trim-lines | 已核实 |
| trough | 2.2.0 | MIT | https://github.com/wooorm/trough | 已核实 |
| unified | 11.0.5 | MIT | https://github.com/unifiedjs/unified | 已核实 |
| unist-util-is | 6.0.1 | MIT | https://github.com/syntax-tree/unist-util-is | 已核实 |
| unist-util-position | 5.0.0 | MIT | https://github.com/syntax-tree/unist-util-position | 已核实 |
| unist-util-stringify-position | 4.0.0 | MIT | https://github.com/syntax-tree/unist-util-stringify-position | 已核实 |
| unist-util-visit | 5.2.0 | MIT | https://github.com/syntax-tree/unist-util-visit | 已核实 |
| unist-util-visit-parents | 6.1.0 | MIT | https://github.com/syntax-tree/unist-util-visit-parents | 已核实 |
| vfile | 6.0.3 | MIT | https://github.com/vfile/vfile | 已核实 |
| vfile-message | 4.0.4 | MIT | https://github.com/vfile/vfile-message | 已核实 |
| zustand | 5.1.0 | MIT | https://github.com/pmndrs/zustand | 已核实 |
| zwitch | 2.0.4 | MIT | https://github.com/wooorm/zwitch | 已核实 |

## Android 运行时（包含在 APK 中）

| 组件 | 版本 | 许可证 | 来源 | 状态 |
| --- | --- | --- | --- | --- |
| @capacitor/android | 8.6.2 | MIT | https://github.com/ionic-team/capacitor | 已核实 |
| androidx.activity:activity | 1.11.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.annotation:annotation | 1.8.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.annotation:annotation-experimental | 1.4.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.annotation:annotation-jvm | 1.8.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.appcompat:appcompat | 1.7.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.appcompat:appcompat-resources | 1.7.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.arch.core:core-common | 2.2.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.arch.core:core-runtime | 2.2.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.collection:collection | 1.4.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.collection:collection-jvm | 1.4.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.concurrent:concurrent-futures | 1.1.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.coordinatorlayout:coordinatorlayout | 1.3.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.core:core | 1.17.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.core:core-ktx | 1.17.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.core:core-splashscreen | 1.2.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.core:core-viewtree | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.cursoradapter:cursoradapter | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.customview:customview | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.drawerlayout:drawerlayout | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.emoji2:emoji2 | 1.3.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.emoji2:emoji2-views-helper | 1.3.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.fragment:fragment | 1.8.9 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.interpolator:interpolator | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.lifecycle:lifecycle-common | 2.6.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.lifecycle:lifecycle-livedata | 2.6.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.lifecycle:lifecycle-livedata-core | 2.6.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.lifecycle:lifecycle-process | 2.6.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.lifecycle:lifecycle-runtime | 2.6.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.lifecycle:lifecycle-viewmodel | 2.6.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.lifecycle:lifecycle-viewmodel-savedstate | 2.6.2 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.loader:loader | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.profileinstaller:profileinstaller | 1.4.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.resourceinspection:resourceinspection-annotation | 1.0.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.savedstate:savedstate | 1.2.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.startup:startup-runtime | 1.1.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.tracing:tracing | 1.2.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.vectordrawable:vectordrawable | 1.1.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.vectordrawable:vectordrawable-animated | 1.1.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.versionedparcelable:versionedparcelable | 1.1.1 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.viewpager:viewpager | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| androidx.webkit:webkit | 1.14.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| capacitor-secure-storage-plugin | 0.14.2 | MIT | https://github.com/martinkasa/capacitor-secure-storage-plugin | 已核实 |
| com.google.guava:listenablefuture | 1.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.apache.cordova:framework | 14.0.1 | Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.jetbrains:annotations | 23.0.0 | Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.jetbrains.kotlin:kotlin-stdlib | 2.0.21 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.jetbrains.kotlinx:kotlinx-coroutines-android | 1.8.1 | Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.jetbrains.kotlinx:kotlinx-coroutines-bom | 1.8.1 | Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.jetbrains.kotlinx:kotlinx-coroutines-core | 1.8.1 | Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.jetbrains.kotlinx:kotlinx-coroutines-core-jvm | 1.8.1 | Apache-2.0 | https://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |
| org.jspecify:jspecify | 1.0.0 | Apache-2.0 | http://www.apache.org/licenses/LICENSE-2.0.txt | 已核实 |

## iOS（Xcode 工程）

| 组件 | 版本 | 许可证 | 来源 | 状态 |
| --- | --- | --- | --- | --- |
| @capacitor/ios（Capacitor 运行时源码） | 8.6.2 | MIT | https://github.com/ionic-team/capacitor | 已核实 |
| capacitor-secure-storage-plugin（iOS Keychain） | 0.14.2 | MIT | https://github.com/martinkasa/capacitor-secure-storage-plugin | 已核实 |
| capacitor-swift-pm（SwiftPM 包装仓库） | 8.6.2 | MIT | https://github.com/ionic-team/capacitor-swift-pm | 已核实 |

## 素材说明

- 应用图标（`public/icons/*.png`、`public/icon.svg`）由本项目脚本 `scripts/gen-icons.mjs` 生成，无第三方素材。
- 界面图标来自 lucide-react（ISC 许可证，已在上表列入），以 SVG 组件形式打包，不是独立素材文件。
- 未打包任何第三方字体或音频文件；界面使用系统字体，Emoji 由用户设备字体渲染。

## 许可证全文

以下文本逐字取自各组件自带的许可证文件，未做删改。

### MIT

适用于：@capacitor/core@8.6.2、Android · @capacitor/android@8.6.2、iOS · @capacitor/ios（Capacitor 运行时源码）@8.6.2

````text
MIT License

Copyright (c) 2017-present Drifty Co.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

### ISC

适用于：@ungap/structured-clone@1.4.0

````text
ISC License

Copyright (c) 2021, Andrea Giammarchi, @WebReflection

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY
AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE
OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
PERFORMANCE OF THIS SOFTWARE.
````

### MIT

适用于：bail@2.0.2、ccount@2.0.1、mdast-util-to-string@4.0.0、unist-util-position@5.0.0

````text
(The MIT License)

Copyright (c) 2015 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：capacitor-secure-storage-plugin@0.14.2、Android · capacitor-secure-storage-plugin@0.14.2、iOS · capacitor-secure-storage-plugin（iOS Keychain）@0.14.2

````text
MIT License

Copyright (c) 2019 martinkasa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

### MIT

适用于：comma-separated-tokens@2.0.3、hast-util-whitespace@3.0.0、space-separated-tokens@2.0.2、unist-util-stringify-position@4.0.0、zwitch@2.0.4

````text
(The MIT License)

Copyright (c) 2016 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：cookie@1.1.1

````text
(The MIT License)

Copyright (c) 2012-2014 Roman Shtylman <shtylman@gmail.com>
Copyright (c) 2015 Douglas Christopher Wilson <doug@somethingdoug.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：decode-named-character-reference@1.3.0、hast-util-to-jsx-runtime@2.3.7、markdown-table@3.1.0、mdast-util-find-and-replace@3.0.4、mdast-util-from-markdown@2.1.0、mdast-util-gfm@3.1.0、mdast-util-gfm-autolink-literal@2.1.0、mdast-util-gfm-footnote@2.1.0、mdast-util-gfm-strikethrough@2.0.1、mdast-util-gfm-table@2.0.1、mdast-util-gfm-task-list-item@2.0.1、mdast-util-to-hast@13.2.2、mdast-util-to-markdown@2.2.3、micromark@4.0.3、micromark-core-commonmark@2.0.4、micromark-extension-gfm-table@2.1.2、micromark-factory-destination@2.0.1、micromark-factory-label@2.0.1、micromark-factory-space@2.1.0、micromark-factory-title@2.0.1、micromark-factory-whitespace@2.0.1、micromark-util-character@2.1.1、micromark-util-chunked@2.0.1、micromark-util-classify-character@2.0.1、micromark-util-combine-extensions@2.0.1、micromark-util-decode-numeric-character-reference@2.0.2、micromark-util-decode-string@2.0.1、micromark-util-edit-map@1.0.0、micromark-util-encode@2.0.1、micromark-util-html-tag-name@2.0.1、micromark-util-normalize-identifier@2.0.1、micromark-util-resolve-all@2.0.1、micromark-util-sanitize-uri@2.0.1、micromark-util-subtokenize@2.1.0、remark-gfm@4.0.1、remark-rehype@11.1.2、unist-util-visit@5.2.0、unist-util-visit-parents@6.1.0、vfile-message@4.0.4

````text
(The MIT License)

Copyright (c) Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：devlop@1.1.0

````text
(The MIT License)

Copyright (c) 2023 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：escape-string-regexp@5.0.0、is-plain-obj@4.1.0

````text
MIT License

Copyright (c) Sindre Sorhus <sindresorhus@gmail.com> (https://sindresorhus.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：estree-util-is-identifier-name@3.0.0、micromark-extension-gfm@3.0.0、micromark-extension-gfm-autolink-literal@2.1.0、micromark-extension-gfm-strikethrough@2.1.0、micromark-extension-gfm-tagfilter@2.0.0、micromark-extension-gfm-task-list-item@2.1.0

````text
(The MIT License)

Copyright (c) 2020 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：extend@3.0.2

````text
The MIT License (MIT)

Copyright (c) 2014 Stefan Thomas

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：html-url-attributes@3.0.1

````text
(The MIT License)

Copyright (c) Titus Wormer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
````

### MIT

适用于：inline-style-parser@0.2.9

````text
(The MIT License)

Copyright (c) 2012 TJ Holowaychuk <tj@vision-media.ca>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：longest-streak@3.1.0、trim-lines@3.0.1

````text
(The MIT License)

Copyright (c) 2015 Titus Wormer <mailto:tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### ISC

适用于：lucide-react@1.74.0

````text
ISC License

Copyright (c) 2026 Lucide Icons and Contributors

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

---

The following Lucide icons are derived from the Feather project:

airplay, alert-circle, alert-octagon, alert-triangle, aperture, arrow-down-circle, arrow-down-left, arrow-down-right, arrow-down, arrow-left-circle, arrow-left, arrow-right-circle, arrow-right, arrow-up-circle, arrow-up-left, arrow-up-right, arrow-up, at-sign, calendar, cast, check, chevron-down, chevron-left, chevron-right, chevron-up, chevrons-down, chevrons-left, chevrons-right, chevrons-up, circle, clipboard, clock, code, columns, command, compass, corner-down-left, corner-down-right, corner-left-down, corner-left-up, corner-right-down, corner-right-up, corner-up-left, corner-up-right, crosshair, database, divide-circle, divide-square, dollar-sign, download, external-link, feather, frown, hash, headphones, help-circle, info, italic, key, layout, life-buoy, link-2, link, loader, lock, log-in, log-out, maximize, meh, minimize, minimize-2, minus-circle, minus-square, minus, monitor, moon, more-horizontal, more-vertical, move, music, navigation-2, navigation, octagon, pause-circle, percent, plus-circle, plus-square, plus, power, radio, rss, search, server, share, shopping-bag, sidebar, smartphone, smile, square, table-2, tablet, target, terminal, trash-2, trash, triangle, tv, type, upload, x-circle, x-octagon, x-square, x, zoom-in, zoom-out

The MIT License (MIT) (for the icons listed above)

Copyright (c) 2013-present Cole Bemis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

### MIT

适用于：mdast-util-phrasing@4.1.0

````text
(The MIT License)

Copyright (c) 2017 Titus Wormer <tituswormer@gmail.com>
Copyright (c) 2017 Victor Felder <victor@draft.li>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：micromark-extension-gfm-footnote@2.1.0

````text
(The MIT License)

Copyright (c) 2021 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：property-information@7.2.0

````text
(The MIT License)

Copyright (c) Titus Wormer <mailto:tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：react@19.3.1、react-dom@19.3.1、scheduler@0.28.0

````text
MIT License

Copyright (c) Meta Platforms, Inc. and affiliates.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

### MIT

适用于：react-markdown@10.1.0

````text
The MIT License (MIT)

Copyright (c) Espen Hovlandsdal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

### MIT

适用于：react-router@7.18.5、react-router-dom@7.18.5

````text
MIT License

Copyright (c) React Training LLC 2015-2019
Copyright (c) Remix Software Inc. 2020-2021
Copyright (c) Shopify Inc. 2022-2023

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

### MIT

适用于：remark-parse@11.0.0

````text
(The MIT License)

Copyright (c) 2014 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
````

### MIT

适用于：set-cookie-parser@2.7.3

````text
The MIT License (MIT)

Copyright (c) 2015 Nathan Friedly <nathan@nfriedly.com> (http://nfriedly.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
````

### MIT

适用于：style-to-object@2.0.2

````text
The MIT License (MIT)

Copyright (c) 2017 Menglin "Mark" Xu <mark@remarkablemark.org>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：trough@2.2.0

````text
(The MIT License)

Copyright (c) 2016 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
````

### MIT

适用于：unified@11.0.5、vfile@6.0.3

````text
(The MIT License)

Copyright (c) 2015 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
````

### MIT

适用于：unist-util-is@6.0.1

````text
(The MIT license)

Copyright (c) 2015 Titus Wormer <tituswormer@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
````

### MIT

适用于：zustand@5.1.0

````text
MIT License

Copyright (c) 2019 Paul Henschel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

### Apache-2.0

适用于：Android · androidx.activity:activity@1.11.0、Android · androidx.annotation:annotation@1.8.1、Android · androidx.annotation:annotation-experimental@1.4.1、Android · androidx.annotation:annotation-jvm@1.8.1、Android · androidx.appcompat:appcompat@1.7.1、Android · androidx.appcompat:appcompat-resources@1.7.1、Android · androidx.arch.core:core-common@2.2.0、Android · androidx.arch.core:core-runtime@2.2.0、Android · androidx.collection:collection@1.4.2、Android · androidx.collection:collection-jvm@1.4.2、Android · androidx.concurrent:concurrent-futures@1.1.0、Android · androidx.coordinatorlayout:coordinatorlayout@1.3.0、Android · androidx.core:core@1.17.0、Android · androidx.core:core-ktx@1.17.0、Android · androidx.core:core-splashscreen@1.2.0、Android · androidx.core:core-viewtree@1.0.0、Android · androidx.cursoradapter:cursoradapter@1.0.0、Android · androidx.customview:customview@1.0.0、Android · androidx.drawerlayout:drawerlayout@1.0.0、Android · androidx.emoji2:emoji2@1.3.0、Android · androidx.emoji2:emoji2-views-helper@1.3.0、Android · androidx.fragment:fragment@1.8.9、Android · androidx.interpolator:interpolator@1.0.0、Android · androidx.lifecycle:lifecycle-common@2.6.2、Android · androidx.lifecycle:lifecycle-livedata@2.6.2、Android · androidx.lifecycle:lifecycle-livedata-core@2.6.2、Android · androidx.lifecycle:lifecycle-process@2.6.2、Android · androidx.lifecycle:lifecycle-runtime@2.6.2、Android · androidx.lifecycle:lifecycle-viewmodel@2.6.2、Android · androidx.lifecycle:lifecycle-viewmodel-savedstate@2.6.2、Android · androidx.loader:loader@1.0.0、Android · androidx.profileinstaller:profileinstaller@1.4.0、Android · androidx.resourceinspection:resourceinspection-annotation@1.0.1、Android · androidx.savedstate:savedstate@1.2.1、Android · androidx.startup:startup-runtime@1.1.1、Android · androidx.tracing:tracing@1.2.0、Android · androidx.vectordrawable:vectordrawable@1.1.0、Android · androidx.vectordrawable:vectordrawable-animated@1.1.0、Android · androidx.versionedparcelable:versionedparcelable@1.1.1、Android · androidx.viewpager:viewpager@1.0.0、Android · androidx.webkit:webkit@1.14.0、Android · com.google.guava:listenablefuture@1.0、Android · org.apache.cordova:framework@14.0.1、Android · org.jetbrains:annotations@23.0.0、Android · org.jetbrains.kotlin:kotlin-stdlib@2.0.21、Android · org.jetbrains.kotlinx:kotlinx-coroutines-android@1.8.1、Android · org.jetbrains.kotlinx:kotlinx-coroutines-bom@1.8.1、Android · org.jetbrains.kotlinx:kotlinx-coroutines-core@1.8.1、Android · org.jetbrains.kotlinx:kotlinx-coroutines-core-jvm@1.8.1、Android · org.jspecify:jspecify@1.0.0

````text
Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "[]"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright [yyyy] [name of copyright owner]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
````

### MIT

适用于：iOS · capacitor-swift-pm（SwiftPM 包装仓库）@8.6.2

````text
The MIT License (MIT)

Copyright (c) 2022-present Drifty Co.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Third-party components, software, and/or libraries (collectively, "components") are included under the licenses specified by their authors. For information about these third-party licenses, refer to the separate legal notices governing such components at NOTICE file at the top level of the package.
````

