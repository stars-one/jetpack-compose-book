
## Jetpack Compose
如果你想为 Jetpack Compose 做贡献的话，你可以加入 [Kotlin](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) 的 Slack 频道 #Compose, 或者在 [https://issuetracker.google.com/issues?q=componentid:612128](https://issuetracker.google.com/issues?q=componentid:612128) 中提交 Compose 的 Bug 或者错误


## 本项目
我们非常欢迎各种的 PR 请求，_(:з)∠)_本项目还处于初期阶段，非常需要各位大佬的完善和纠错

文档采用 [Material 主题的 MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/) 来编辑，非常好上手,你只需要按照以下的步骤:

* 安装插件

```
    pip3 install mkdocs-minify-plugin
    pip3 install mkdocs-git-revision-date-localized-plugin
    pip3 install mkdocs-minify-plugin
    pip3 install mkdocs-macros-plugin
```

* 在本地运行和测试

    终端执行 ``` mkdocs serve ```，将会在 ``` http://localhost:8000/ ``` 看到文档


* 如何添加/更改文档？
    
    文档都是由 **Markdown** 语法来编写的，所有文档位于 [/docs](https://github.com/Compose-Museum/Compose-Tutorial/tree/main/docs) 中, 如果需要扩展左边的导航侧栏，请在 **mkdocs.yml** 更新 **nav**

* 最后

    恭喜你，当你同步了本项目的最新进度并且添加了你所想的东西，你只需要提交 PR 即可，我们在审核通过会自动同步到网站上