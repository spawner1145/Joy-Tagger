# Joy-Tagger
- 使用fancyfeast/llama-joycaption-alpha-two-hf-llava模型给一个压缩包里的图片打标并写进图片的exif里
- 模型modelscope地址https://www.modelscope.cn/models/shiertier/llama-joycaption-alpha-two-hf-llava
- 使用了accelerate等一些措施自动分配多显卡时的占用
- 结束后会在指定路径生成一个压缩包，里面是打好标的图片
