# 标题
## 可爱的小标记
:pushpin: 
:white_check_mark: 

* :weight_lifting: 
* :weight_lifting_woman: 
* :weight_lifting_woman: 

- 1
  - 1.1
- 2
  - 2.1

* 1
  * 1.1
* 2
  * 2.1


:question: **问题1:** `train_step = PythonScriptStep(name="train-step", ...)` 在哪里设置相关的Python依赖?
<details>
  <summary>:white_check_mark: See solution!</summary>

实验中通过在Notebook中创建的AML environment `workshop-env`来定义python相关依赖。该环境加载了一个`conda.yml`，这里定义了所有python的依赖库

</details>