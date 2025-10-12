# MIRAGE: Masked Imitation for Robotic Action Generation and Execution

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/tonywang-0517/Mirage)
[![Project](https://img.shields.io/badge/Project-Page-green)](https://tonywang-0517.github.io/mirage.github.io/)

Project page for **MIRAGE: Masked Imitation for Robotic Action Generation and Execution** by Puyue Wang (University of Auckland, COMPSCI 792 Project - 2025).

A lightweight execution framework for robust whole-body humanoid control with standardized data, enhancing robustness and decoupling execution from upstream planning.

## Overview

Vision–Language–Action (VLA) systems have advanced semantic reasoning for robots, yet achieving robust whole-body humanoid control that couples semantic understanding with dynamic adaptability remains a central challenge. MIRAGE introduces three key innovations:

- **SCHEMA** (Sparse Command Handling for Embodied Motion Abstraction): Unified sparse-joint protocol based on SMPL-X key body joints
- **MIRROR** (Memory-Integrated Robust Representation for Online Robustness): Leverages action-state histories for robust control under domain shifts
- **RISE** (Recovery via Inferred State Endpoints): Distills expert recoveries for long-horizon behaviors like fall-and-get-up

## Key Results

- **∼17%** trajectory error reduction
- **∼16 percentage points** strict success improvement
- **∼34 points** push-recovery improvement
- **61%** fall-recovery success rate (vs. 0% baseline)
- **75.9%** sim-to-sim transfer success (vs. 0.7% baseline)

## Links

- **GitHub Repository**: [https://github.com/tonywang-0517/Mirage](https://github.com/tonywang-0517/Mirage)
- **Project Mural**: [View on Mural](https://app.mural.co/t/puyuewangsworkspace5613/m/unicornai4709/1754387147784/6803cde2dd3d1ec8035077a659d47cdce2261ad6?sender=u18823d8b8a2cf6ec54a84733)
- **Author**: [Puyue Wang](https://github.com/tonywang-0517)

## Project Structure

```
mirage.github.io/
├── index.html              # Main project page
├── static/
│   ├── css/               # Stylesheets
│   ├── js/                # JavaScript files
│   ├── images/            # Images and visualizations
│   │   ├── poster_banner.jpg           # Hero section background
│   │   ├── structure_overview.jpg      # Framework overview
│   │   ├── teacher_training_stage1.jpg # Training stage 1
│   │   ├── student_training_stage2.jpg # Training stage 2
│   │   ├── mirage_eval_process.jpg     # Evaluation process
│   │   ├── method_comparison.png       # Method comparison
│   │   ├── metrics_comparison.png      # Performance metrics
│   │   ├── terrain.png                 # Terrain diversity
│   │   └── favicon.ico                 # Site favicon
│   ├── videos/            # Demo videos
│   │   ├── g1_genesis_walk_g1.mp4      # Genesis simulator demo
│   │   └── g1_isaaclab_walk_demo.mp4   # IsaacLab simulator demo
│   └── pdfs/              # Papers and posters
└── README.md              # This file
```

## Features

- **Hero Section**: Eye-catching introduction with gradient design
- **Performance Metrics**: Interactive cards showcasing key results
- **Demo Videos**: Carousel of G1 humanoid demonstrations in different simulators
- **Training Pipeline**: Two-stage teacher-student training visualization
- **Evaluation Framework**: Comprehensive testing across multiple dimensions
- **Method Comparison**: Side-by-side comparison with baseline approaches
- **Quantitative Results**: Detailed performance metrics visualization
- **Terrain Diversity**: Analysis across varied environmental conditions

## Citation

```bibtex
@misc{wang2025mirage,
  title={MIRAGE: Masked Imitation for Robotic Action Generation and Execution},
  author={Wang, Puyue},
  year={2025},
  institution={University of Auckland},
  note={COMPSCI 792 Project},
  url={https://github.com/tonywang-0517/Mirage}
}
```

## Development

The project page uses modern web technologies:
- **Bulma CSS** framework for responsive design
- **Font Awesome** for icons
- **Bulma Carousel** for image/video carousels
- **Custom gradient styles** for brand consistency
- Optimized for performance and SEO

## Media Assets

### Images
All images are properly referenced and positioned:
- `poster_banner.jpg` - Used as hero section background overlay
- `structure_overview.jpg` - Framework pipeline diagram & video poster
- `teacher_training_stage1.jpg` - Stage 1 training visualization
- `student_training_stage2.jpg` - Stage 2 training visualization
- `mirage_eval_process.jpg` - Evaluation methodology & video poster
- `method_comparison.png` - Comparison with baseline methods
- `metrics_comparison.png` - Quantitative performance charts
- `terrain.png` - Terrain diversity analysis

### Videos
- `g1_genesis_walk_g1.mp4` - G1 humanoid walking in Genesis simulator
- `g1_isaaclab_walk_demo.mp4` - G1 humanoid sim-to-sim transfer in IsaacLab

## Acknowledgments

This project page design was inspired by the [ODYSSEY](https://github.com/) project page and built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template).

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
