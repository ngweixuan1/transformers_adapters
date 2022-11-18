# Deep-Learning-Projects

## Adapters Project

Pre-training transformer language models with domain or task data followed by fine-tuning has shown to improve performance for natural language processing tasks. However, such pre-training and fine-tuning approach suffers from high requirements of computation resources and low portability due to the large model size. Recently, adapters have demonstrated a parameter-efficient solution to achieve similar performance as full fine-tuning on the GLUE benchmark. To study adapter’s effectiveness, we apply adapters to RoBERTa baseline model [9] and fine-tuning on all the tasks and domains in Gururangan et. al (2020) [4]. Adapters attained near state-of-the-art performance and achieved comparable results as TAPT and DAPT model for SCIERC and HYPERPARTISAN respectively, which demonstrates
adapter’s potential as parameter-efficient training strategy.

@inproceedings{pfeiffer2020AdapterHub,
    title={AdapterHub: A Framework for Adapting Transformers},
    author={Pfeiffer, Jonas and
            R{\"u}ckl{\'e}, Andreas and
            Poth, Clifton and
            Kamath, Aishwarya and
            Vuli{\'c}, Ivan and
            Ruder, Sebastian and
            Cho, Kyunghyun and
            Gurevych, Iryna},
    booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: System Demonstrations},
    pages={46--54},
    year={2020}
}s