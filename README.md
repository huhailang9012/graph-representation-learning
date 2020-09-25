# Graph-Representation-Learning
图表示学习

# 写在前面的话
最近我在校准翻译的时候常常在想，我们这个翻译文档的版本如何管理维护？思考两个问题：
一、游卉擎在校准，王蓉在校准，我也在校准，但是我们手里拿到了文档却是三个不同版本的文档，那么大家校准完以后如何合并呢？
二、大家都在校准，如果出现了校准部分重叠了怎么办，岂不是在重复造轮子（编程里面经典用语，用于形容那些不断重复编码，做无用功）？

# 我们的目标
我们的目标是大家手里拿的永远是最新版本的文档，何为最新？即，各位最后一次提交的版本，然后在这个版本基础上修改校准，并且可以规避重复校准。
大家也许会问，为什么不用腾讯在线文档编辑，何必来学一个新工具？我的答案是
一、在线文档编辑不适合较大的文档，像几十兆上百兆的文档，腾讯在线文档工具难以应付；
二、更重要的教会大家使用一个以后工作息息相关的文档或代码的版本管理工具。

# 引入代码或文档版本管理工具
我们现在的文档，包括以后我们编程的代码，只要大家以后做编程或与编程相关的工作，无一例外地会用到版本管理工具，我分享一个目前企业界最流行的工具：git

# 使用方式
一、安装git.exe
二、在文档存储的目录下，点击右键，选择Git Bash Here
三、输入命令：git clone 
四、在电脑本地修改文档
五、输入命令: git add all
六、输入命令：git commit -m ""
七、输入命令：git push origin master

下面我来讲讲关键的三、五、六、七步
三、从远程仓库服务器拉取文档到本地电脑，文档从无到有
五、我们本地修改完文档以后，讲修改部分存储在本地缓存
六、对我们的修改部分进行注释说明，双引号内写注释
七、将我们的修改提交到远程仓库

# 注意
一、远程仓库共享一份文档，我们拉取最新文档，然后本地修改，最后提交修改到远程仓库，这就保证了上面所讲的我们永远能拿到最新版本的文档
二、对我们的修改部分进行注释说明时，工具是没法对我们写了什么内容进行约束的，所以我们要以高要求约束自己，一定要细致，比方说我改了哪一章，或者我改了哪几页，写的明明白白，这样做的好处是其他人看了这个注释说明以后，就不会去修改同样的部分，避免重复修改。

# 写在最后的话
图表示学习，是向老师要求我们重点学习的第一篇论文，也是我们研究生生涯接触的第一篇论文，其重要性不言而喻，希望我们能将这篇翻译文稿做成精品文稿，大家齐心协力，咬文嚼字、反复阅读，争取弄懂每一个概念和公式，把它玩透、吃透，以此篇论文作为范本开启我们研究生科研学习之旅!

