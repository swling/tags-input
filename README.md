# tags-input
Custom tags input based on JQuery and bulma CSS

@link https://github.com/neveresthub/tags-input

# change
## v1.0
- 样式按bulma修改
- 新增一个hidden input，自动绑定tags input value，无需额外JavaScript代码，可直接提交表单
- 新增最大标签数目限制。定义变量：_max_tag_num
- 新增标签时，检测当前标签是否已存在，避免重复
- 优化 ajax 请求条件，仅当前输入有效发送，检测当前输入是否发生变动，避免无效键盘触发，降低无效ajax请求
- 其他一些细节优化
# Usage
See index.html 

