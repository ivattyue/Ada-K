<h1 align='center' style="text-align:center; font-weight:bold; font-size:2.0em;letter-spacing:2.0px;"> Ada-K Routing: Boosting the Efficiency of MoE-based LLMs </h1>

<p align='center' style="text-align:center;font-size:1.25em;">
    <a href="https://scholar.google.com/citations?user=OrICiVQAAAAJ&hl=zh-CN" target="_blank" style="text-decoration: none;">Tongtian Yue<sup>1,2</sup></a>&nbsp;,&nbsp;
    <a href="https://scholar.google.com/citations?user=OaGRHWYAAAAJ&hl=zh-CN" target="_blank" style="text-decoration: none;">Longteng Guo<sup>1,2</sup></a>&nbsp;,&nbsp;
    <a href="https://scholar.google.com/citations?user=IOiro9MAAAAJ&hl=zh-CN" target="_blank" style="text-decoration: none;">Jie Cheng<sup>1,2</sup></a>&nbsp;,&nbsp;
    <a href="https://scholar.google.com/citations?user=AZSVH9sAAAAJ&hl=zh-CN" target="_blank" style="text-decoration: none;">Xuange Gao<sup>1,2</sup></a>&nbsp;,&nbsp;
  <a href="https://scholar.google.com/citations?user=EplUB7oAAAAJ&hl=zh-CN" target="_blank" style="text-decoration: none;">Hua Huang<sup>1,2</sup></a>&nbsp;,&nbsp;
    <a href="https://scholar.google.com/citations?user=sOI-S7oAAAAJ&hl=zh-CN" target="_blank" style="text-decoration: none;">Jing Liu<sup>1,3†</sup></a>&nbsp;&nbsp;
	<br>
<sup>1</sup>Institute of Automation, Chinese Academy of Sciences&nbsp;&nbsp;&nbsp;<br>
<sup>2</sup>School of Artificial Intelligence, University of Chinese Academy of Sciences&nbsp;&nbsp;&nbsp;<br>
<sup>3</sup>School of Artificial Intelligence, Beijing Normal University&nbsp;&nbsp;&nbsp;
</p>

<p align='center';>
<b>
<em>ICLR, 2025</em> <br>
</b>
</p>



<!-- ## Abstract

In the era of Large Language Models (LLMs), Mixture-of-Experts (MoE) architectures offer a promising approach to managing computational costs while scaling up model parameters. Conventional MoE-based LLMs typically employ static Top-k routing, which activates a fixed and equal number of experts for each token regardless of their significance within the context. In this paper, we propose a novel Ada-k routing strategy that dynamically adjusts the number of activated experts for each token, thereby improving the balance between computational efficiency and model performance. Specifically, our strategy incorporates learnable and lightweight allocator modules that decide customized expert resource allocation tailored to the contextual needs for each token. These allocators are designed to be fully pluggable, making it broadly applicable across all mainstream MoE-based LLMs. We leverage the Proximal Policy Optimization (PPO) algorithm to facilitate an end-to-end learning process for this non-differentiable decision-making framework. Extensive evaluations on four popular baseline models demonstrate that our Ada-k routing method significantly outperforms conventional Top-k routing. Compared to Top-k, our method achieves over 25\% reduction in FLOPs and more than 20% inference speedup while still improving performance across various benchmarks. Moreover, the training of Ada-k is highly efficient. Even for Mixtral-8x22B, a MoE-based LLM with more than 140B parameters, the training time is limited to 8 hours. Detailed analysis shows that harder tasks, middle layers, and content words tend to activate more experts, providing valuable insights for future adaptive MoE system designs. -->
