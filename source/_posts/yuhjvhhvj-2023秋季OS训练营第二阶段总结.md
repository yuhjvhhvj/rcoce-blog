---
title: yuhjvhhvj-2023秋季OS训练营第二阶段总结
date: 2023-11-08 20:06:41
categories:
    - report
tags:
    - author:yuhjvhhvj
    - repo:https://github.com/LearningOS/2023a-rcore-yuhjvhhvj
---

感谢老师和助教们贡献了这么好的课程，老师们不仅提供了详细的教材，还有进行了大量的直播授课，其中还会对作业进行讲解！！没有作业的直播讲解，我很有可能就坚持不下来了，再次感谢老师们的直播授课！
<!-- more -->
# 实验1
在实验1中，实验要求我引入一个新的系统调用 sys_task_info 以获取当前任务的信息。在一开始，其实我真的一点头绪都没有，完全不知道从哪下手，但是在反复阅读教材的第三章后，对TCB，任务管理有着更深入的理解后，我才开始逐渐明确我需要从哪入手。在完成这个实验后，我对如何维护控制块信息有了更深入的了解。
# 实验2
在实验2中，这次的操作系统引入虚存机制了，实验要求重写内核的 sys_get_time 和 sys_task_info 函数实现，并完成mmap 和 munmap 匿名映射功能。在完成实验的过程中，主要是卡在了如何检查已经被映射的页，解决了这一点后，这个实验难度还是比较低的，不过也让我对地址空间，多级页表这些概念有了更清晰的认知。
# 实验3
在实验3中，实验要求实现一个完全 DIY 的系统调用 spawn，用以创建一个新进程，并实现stride调度算法。前者在理解进程等概念后还是比较简单的，但是在实现stride调度算法时，由于一开始对操作中任务切换这一块不够清晰，导致我不知道从何下手，不过听完在老师的作业讲解后，还是很快就理清了思路，完成了实验。
# 最后的最后
现在只完成了前3个实验，在后续会尽量把后俩个实验完成。