file(GLOB_RECURSE tmp *.mm *.cc)
set(Caffe2_CPU_SRCS ${Caffe2_CPU_SRCS} ${tmp} PARENT_SCOPE)
