# Web Workers Demo

Migrate Long Running JS onto a Web Worker

## [Relevant Quiz from Browser Rendering Optimization](https://www.udacity.com/course/viewer#!/c-ud860/l-4138168623/e-4184098558/m-4150829139)

## [Relevant solution from Browser Rendering Optimization](https://www.udacity.com/course/viewer#!/c-ud860/l-4138168623/e-4184098558/m-4146278980)

Working on the quiz? Start by examining index.html and the JavaScript files linked inside it.

- cpu 密集计算可以通过 `web worker` 在另外一个线程执行防止主线程卡顿（性能优化）
- 经常使用的对象应该缓存起来减少垃圾收集的次数和规模（内存优化）
