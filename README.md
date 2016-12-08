###自定义View与自定义ViewGroup
上面的是一个可以滑动的刻度尺，支持快速滑动，选择的数字也会显示在下方；下面的是一个经典的流式布局，会根据文字长度自动进行布局。一起看看怎么实现的吧：

![这里写图片描述](http://img.blog.csdn.net/20161122144846668)

###滑动冲突的解决

示例图中是一个常见的下拉回弹，手指向下滑动的时候，整个布局会一起滑动。下拉到一定距离的时候松手，布局会自动回弹到开始的位置；手指向上滑动的时候，布局的子View会滑动到最底部，然后手指再向下滑动，布局的子View会滑动到最顶部，最后手指继续向下滑动，整个布局会一起滑动，下拉到一定距离后松手自动回弹到开始位置。


![这里写图片描述](http://img.blog.csdn.net/20161130214351631)


