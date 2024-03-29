# Waypoint Transformer

## TLDR

Using intermediate target goals and rewards as conditioning variables with behavioral cloning objectives, we can achieve state-of-the-art performance in offline reinforcement learning.

## Abstract

Despite the recent advancements in offline reinforcement learning via supervised learning (RvS) methods and the success of the decision transformer (DT) architecture in various domains, DTs have proven to fall short in the challenging benchmark of maze navigation tasks. The root cause of this underperformance lies in their inability to seamlessly connect segments of suboptimal trajectories, leading to poor performance. To overcome these limitations, we present a novel approach to enhance RvS methods by integrating intermediate targets. We introduce the waypoint transformer (WT), using an architecture that builds upon the DT framework and is further conditioned on dynamically-generated waypoints. The results show a significant improvement in the final return compared to existing RvS methods, with performance on par or greater than existing temporal difference learning-based methods. Additionally, the performance and stability is significantly improved in the most challenging environments and data configurations, including AntMaze Large Play/Diverse and Kitchen Mixed/Partial.
