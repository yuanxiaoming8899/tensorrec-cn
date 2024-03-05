<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">张量记录</font></font></h1><a id="user-content-tensorrec" class="anchor-element" aria-label="永久链接：TensorRec" href="#tensorrec"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 中的 TensorFlow 推荐算法和框架。</font></font></p>
<p dir="auto"><a href="https://badge.fury.io/py/tensorrec" rel="nofollow"><img src="https://camo.githubusercontent.com/da482349eebf61b092ba37f84a3d78fa6897dc61b58e50bee57001d861fbc2d4/68747470733a2f2f62616467652e667572792e696f2f70792f74656e736f727265632e737667" alt="PyPI版本" data-canonical-src="https://badge.fury.io/py/tensorrec.svg" style="max-width: 100%;"></a> <a href="https://travis-ci.org/jfkirk/tensorrec" rel="nofollow"><img src="https://camo.githubusercontent.com/53d24a0c30e6b25d34276d40a0633749e12facd31c30c46251678ff303043767/68747470733a2f2f7472617669732d63692e6f72672f6a666b69726b2f74656e736f727265632e7376673f6272616e63683d6d6173746572" alt="构建状态" data-canonical-src="https://travis-ci.org/jfkirk/tensorrec.svg?branch=master" style="max-width: 100%;"></a> <a href="https://gitter.im/tensorrec" rel="nofollow"><img src="https://camo.githubusercontent.com/d26ba6ceb2f2203f0ef5fb447d780f65a9dc8ea6845a32206f04f77cd41ff2af/68747470733a2f2f6261646765732e6769747465722e696d2f74656e736f727265632f6769747465722e706e67" alt="吉特聊天" data-canonical-src="https://badges.gitter.im/tensorrec/gitter.png" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：TensorRec 尚未积极开发</font></font></h2><a id="user-content-note-tensorrec-is-not-under-active-development" class="anchor-element" aria-label="永久链接：注意：TensorRec 尚未积极开发" href="#note-tensorrec-is-not-under-active-development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorRec 将不会再收到任何计划的更新。</font><font style="vertical-align: inherit;">请随意打开拉取请求——我很高兴审核它们。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢您对 TensorRec 的贡献、支持和使用！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-詹姆斯·柯克，@jfkirk</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于类似的工具，请查看：</font></font></p>
<p dir="auto"><a href="https://github.com/tensorflow/ranking/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorFlow 排名</font></font></a></p>
<p dir="auto"><a href="https://github.com/maciejkula/spotlight"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聚光灯</font></font></a></p>
<p dir="auto"><a href="https://github.com/lyst/lightfm"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">光调频</font></font></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">什么是 TensorRec？</font></font></h2><a id="user-content-what-is-tensorrec" class="anchor-element" aria-label="永久链接：什么是 TensorRec？" href="#what-is-tensorrec"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorRec 是一个 Python 推荐系统，可让您快速开发推荐算法并使用 TensorFlow 进行自定义。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorRec 允许您自定义推荐系统的表示/嵌入函数和损失函数，而 TensorRec 处理数据操作、评分和排名以生成推荐。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorRec 系统消耗三部分数据：</font></font><code>user_features</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>item_features</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>interactions</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">它使用这些数据来学习提出建议并对其进行排名。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 TensorRec 及其用法的概述，请参阅</font></font><a href="https://github.com/jfkirk/tensorrec/wiki"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">wiki。</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关更多信息以及该项目的概要，请阅读</font></font><a href="https://medium.com/@jameskirk1/tensorrec-a-recommendation-engine-framework-in-tensorflow-d85e4f0874e8" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这篇博客文章。</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关构建推荐系统的介绍，请参阅</font></font><a href="https://www.slideshare.net/JamesKirk58/boston-ml-architecting-recommender-systems" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些幻灯片。</font></font></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/jfkirk/tensorrec/master/examples/system_diagram.png"><img src="https://raw.githubusercontent.com/jfkirk/tensorrec/master/examples/system_diagram.png" alt="TensorRec 系统图" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例：基本用法</font></font></h3><a id="user-content-example-basic-usage" class="anchor-element" aria-label="永久链接：示例：基本用法" href="#example-basic-usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-s1">numpy</span> <span class="pl-k">as</span> <span class="pl-s1">np</span>
<span class="pl-k">import</span> <span class="pl-s1">tensorrec</span>

<span class="pl-c"># Build the model with default parameters</span>
<span class="pl-s1">model</span> <span class="pl-c1">=</span> <span class="pl-s1">tensorrec</span>.<span class="pl-v">TensorRec</span>()

<span class="pl-c"># Generate some dummy data</span>
<span class="pl-s1">interactions</span>, <span class="pl-s1">user_features</span>, <span class="pl-s1">item_features</span> <span class="pl-c1">=</span> <span class="pl-s1">tensorrec</span>.<span class="pl-s1">util</span>.<span class="pl-en">generate_dummy_data</span>(
    <span class="pl-s1">num_users</span><span class="pl-c1">=</span><span class="pl-c1">100</span>,
    <span class="pl-s1">num_items</span><span class="pl-c1">=</span><span class="pl-c1">150</span>,
    <span class="pl-s1">interaction_density</span><span class="pl-c1">=</span><span class="pl-c1">.05</span>
)

<span class="pl-c"># Fit the model for 5 epochs</span>
<span class="pl-s1">model</span>.<span class="pl-en">fit</span>(<span class="pl-s1">interactions</span>, <span class="pl-s1">user_features</span>, <span class="pl-s1">item_features</span>, <span class="pl-s1">epochs</span><span class="pl-c1">=</span><span class="pl-c1">5</span>, <span class="pl-s1">verbose</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)

<span class="pl-c"># Predict scores and ranks for all users and all items</span>
<span class="pl-s1">predictions</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">predict</span>(<span class="pl-s1">user_features</span><span class="pl-c1">=</span><span class="pl-s1">user_features</span>,
                            <span class="pl-s1">item_features</span><span class="pl-c1">=</span><span class="pl-s1">item_features</span>)
<span class="pl-s1">predicted_ranks</span> <span class="pl-c1">=</span> <span class="pl-s1">model</span>.<span class="pl-en">predict_rank</span>(<span class="pl-s1">user_features</span><span class="pl-c1">=</span><span class="pl-s1">user_features</span>,
                                     <span class="pl-s1">item_features</span><span class="pl-c1">=</span><span class="pl-s1">item_features</span>)

<span class="pl-c"># Calculate and print the recall at 10</span>
<span class="pl-s1">r_at_k</span> <span class="pl-c1">=</span> <span class="pl-s1">tensorrec</span>.<span class="pl-s1">eval</span>.<span class="pl-en">recall_at_k</span>(<span class="pl-s1">predicted_ranks</span>, <span class="pl-s1">interactions</span>, <span class="pl-s1">k</span><span class="pl-c1">=</span><span class="pl-c1">10</span>)
<span class="pl-en">print</span>(<span class="pl-s1">np</span>.<span class="pl-en">mean</span>(<span class="pl-s1">r_at_k</span>))</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import numpy as np
import tensorrec

# Build the model with default parameters
model = tensorrec.TensorRec()

# Generate some dummy data
interactions, user_features, item_features = tensorrec.util.generate_dummy_data(
    num_users=100,
    num_items=150,
    interaction_density=.05
)

# Fit the model for 5 epochs
model.fit(interactions, user_features, item_features, epochs=5, verbose=True)

# Predict scores and ranks for all users and all items
predictions = model.predict(user_features=user_features,
                            item_features=item_features)
predicted_ranks = model.predict_rank(user_features=user_features,
                                     item_features=item_features)

# Calculate and print the recall at 10
r_at_k = tensorrec.eval.recall_at_k(predicted_ranks, interactions, k=10)
print(np.mean(r_at_k))" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2><a id="user-content-quick-start" class="anchor-element" aria-label="永久链接：快速入门" href="#quick-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorRec 可以通过 pip 安装：
</font></font><code>pip install tensorrec</code></p>
</article></div>
