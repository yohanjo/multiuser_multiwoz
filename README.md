# Multi-User MultiWOZ

## Abstract

While most task-oriented dialogues assume conversations between the agent and one user at a time, dialogue systems are increasingly expected to communicate with multiple users simultaneously who make decisions collaboratively. To facilitate development of such systems, we release the Multi-User MultiWOZ dataset: task-oriented dialogues among two users and one agent. To collect this dataset, each user utterance from MultiWOZ 2.2 was replaced with a small chat between two users that is semantically and pragmatically consistent with the original user utterance, thus resulting in the same dialogue state and system response. These dialogues reflect interesting dynamics of collaborative decision-making in task-oriented scenarios, e.g., social chatter and deliberation. Supported by this data, we propose the novel task of multi-user contextual query rewriting: to rewrite a task-oriented chat between two users as a concise task-oriented query that retains only task-relevant information and that is directly consumable by the dialogue system. We demonstrate that in multi-user dialogues, using predicted rewrites substantially improves dialogue state tracking without modifying existing dialogue systems that are trained for single-user dialogues. Further, this method surpasses training a medium-sized model directly on multi-user dialogues and generalizes to unseen domains.

## Citation
    @inproceedings{Jo.2023.multiuser_multiwoz,
        title = {{Multi-User MultiWOZ: Task-Oriented Dialogues among Multiple Users}}, 
        author = {Jo, Yohan and Zhao, Xinyan and Biswas, Arijit and Basiou, Nikoletta and Auvray, Vincent and Malandrakis, Nikolaos and Metallinou, Angeliki and Potamianos, Alexandros}, 
        booktitle = {Findings of the Association for Computational Linguistics: EMNLP 2023}, 
        year = {2023}, 
        url = {https://openreview.net/forum?id=phJtMADSdy}
    }
