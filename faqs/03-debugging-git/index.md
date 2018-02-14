# 如何定位Git执行过程中的问题

在执行Git命令过程中如果出现一些问题难以定位的时候，，可以通过以下命令打开Git的调试信息 

 

\$env:GIT_TRACE = 1 

\$env:GIT_CURL_VERBOSE=1 

 

使用PowerShell输入以上命令后，Git会非常详细的输出所有的操作的细节，帮助你定位问题。 

 

 
