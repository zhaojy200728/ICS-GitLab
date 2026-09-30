# Lab0: GitLab

Due: 30 Sep, 23:59:59

## TODO

1. 认真阅读[文档](https://ics-26fall-fdu.github.io/labs/lab0-git-lab/)，学习 Git 的基本用法，并在报告中回答文档中的问题。（15 分）

    - 你之前有过多人协同开发的经历吗？如果有，你们是使用什么方式分工协作的？
    - 思考一下，Git 为什么要设计“暂存-提交”两个步骤？
    - `git branch` 和 `git branch -a` 的区别是什么？查阅资料并回答。

2. 使用此仓库建立个人仓库，完成 `main.c` 文件中的 `TODO` 部分并进行一次 commit。（50 分）

   - 只要填入任意字符串就算完成，当然你也可以随意发挥（程序的正确性不纳入计分，有修改即可）。

   - 如果你想要编译运行 `main.c`，执行

   ```bash
   make
   ./main
   make clean
   ```

3. 在下面的三个网页中任选其二进行阅读，简要概括其内容，并谈谈你对“为什么要学习 Git”这个问题的理解。（15 分）

    - [Commit Message 规范](https://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html)
    - [Git Flow 分支控制](https://www.dafaycoding.com/article/git-gif-flow)
    - [语义化版本](https://semver.org/lang/zh-CN/)

4. 学习 Git 分支管理，新建 `feature` 分支，在该分支以及 `main` 分支上对 `main.c` 分别进行一次修改与提交（10 分）。随后将 `feature` 分支 merge 到 `main` 分支（即切换回 main 分支执行 `git merge feature`），并处理发生的合并冲突（10 分）。

    - 在两个分支上的提交必须要满足：在 `main` 分支合并时会出现冲突。请你解决这个冲突，并在实验报告里截图表明你遇到并解决了冲突。

    - 请阅读 `git merge` 部分，思考如何修改 `main.c` 会出现冲突。

    - 如果你两次提交之后合并没有出现冲突，不必担心，你可以不用撤回之前的提交，而是继续尝试提交修改并 merge，直到出现冲突并解决。

5. 在 `main` 分支提交一份实验报告（实验报告单独评分），格式要求为 `PDF` 或 `Markdown`。内容包括：

    - 文档中要求回答的问题
    - 你的实验步骤
    - 必要的截图
    - 你的建议（可选）
