A. 观察该内积过程，对于每个被计算的元素必须加载k个值的应用，我们不可能获得低于k/2的CPE，在这里每个被计算的元素都必须加载2个值，因此任何版本的内积过程都不能达到比1更小的CPE。

B. 浮点运算不满足结合律，即使循环展开也不会减少关键路径上浮点加法的数量。因此浮点数据的性能不会通过循环展开而得到提高。