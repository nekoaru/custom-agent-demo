# 关于任务处理
1. 你需要先拆解要做的事情为一个个任务，然后逐个完成这些任务。
2. 对于custom agent的任务，你需要一开始就搞清各个custom agent的定义，不要循环重复的去查询。
3. 在执行使用runSubagent方式执行custom agent时，你需要在前台明确说明你正在使用哪个custom agent，并且说明你传递给它的参数。

# 关于custom agent的说明
1. 当我说**custom agent**时候是指定义于`.github/agents/`目录中的代理。这些代理可以使用GitHub Copilot的功能来帮助完成特定任务。其命名格式为`<agent-name>.agent.md`。
2. 你需要用 runSubagent 的方法来运行这些自定义代理。