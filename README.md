# The Linguistic Cost of Low-Rank Compression

## Overview

This project investigates how Singular Value Decomposition (SVD) compression affects transformer-based Part-of-Speech taggers.

Rather than focusing solely on parameter reduction, this work examines which linguistic capabilities degrade first under aggressive compression.

## Key Findings

- Small well-trained models retained accuracy despite removing over 94% of attention parameters.
- Mid-rank compression caused catastrophic non-monotonic failures in larger models.
- Proper nouns, verb forms, and modifier distinctions degraded first under compression.

## Technologies

- Python
- PyTorch
- NLP
- Transformers
- Scikit-Learn
- SVD

## Paper

See `paper.pdf` for the full research report.

## Authors

Sarah Randhawa, Chuzhen Ghao, Samuel Ard, and Naseem Uddin

New York University
