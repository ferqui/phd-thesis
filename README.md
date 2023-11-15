# Exploring Learning on Neuromorphic Systems: Towards local and online learning for edge applications

PhD dissertation, Fernando M. Quintana, December 2023. Defended on December 20, 2023.

arXiv: 

Mirrors:

License: BSD 3 clause

Contact: Fernando M. Quintana (fernando.quintana@uca.es)

Please cite using the following BibTex entry:
```
@phdthesis{quintana2023,
  title={Exploring Learning on Neuromorphic Systems: Towards local and online learning for edge applications},
  author={Quintana, Fernando M.},
  school={University of Cádiz, Spain},
  year=2023,
  month=12,
  note={arXiv:}
}
```

---

**Artificial Intelligence (AI)** has experienced significant advances in the last decades, triggering new areas of research and generating unprecedented demands. Despite this progress, it is imperative to recognise that such systems require increasing computational power and databases of ever-increasing magnitude. Although current developments in lithography still allow the miniaturisation of electronic components, transistors are approaching atomic scale and production costs are scaling proportionally. This situation means that the computational demands of AI systems may become unsustainable from a technical, economic and environmental perspective. In this context, **neuromorphic systems** emerge as a new computational paradigm. Inspired by biology, where memory and processing are co-localised and distributed, different from the classical Von Neumann architecture; promises remarkable improvements in energy efficiency and computational capacity. However, this new computation paradigm introduces significant challenges on learning, making conventional machine learning techniques not directly applicable. In the framework of this research, the focus has been on the development and implementation of learning techniques for **Spiking Neural Networks (SNNs)**. This PhD thesis introduced **ETLP**, an innovative local learning rule that enables multi-layer learning. Furthermore, its potential to be implemented in hardware was evaluated, and the implementation of **R-STDP**, another local learning technique, was carried out, obtaining comparable results between software simulations and hardware implementation. As a culmination, a simulator for a mixed-signal processor, DynapSEtorch, has been developed for **DPI circuits**. This tool enables the developmend and validation of new algorithms and learning techniques before their chip implementation, ensuring their feasibility. It has been tested on the Dynap-SE chip, showing comparable results between simulations and hardware emulations. Additionally, ETLP has been simulated in DynapSEtorch and deployed directly on the Dynap-SE chip, proving its compatibility with DPI-based neurons.
