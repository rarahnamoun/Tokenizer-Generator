# Automatic Tokenizer Generator for Low-Resource Languages 
[![Technical Report](https://img.shields.io/badge/Technical%20Report-PDF-blue)](https://github.com/rarahnamoun/Tokenizer-Generator/blob/main/report.pdf)
<br/>
A self-adapting tokenization system that automatically generates and implements optimal tokenization strategies based on input text characteristics.
## Overview
This project introduces an innovative language-independent system that automatically generates and implements tokenizer algorithms based on input text characteristics. While specifically validated on Persian as a low-resource language case study, the system can adapt to various languages and text challenges through its automatic generation capabilities.
## Key Features
- **Automatic Tokenizer Generation**: System analyzes input text and generates optimal tokenization strategies
- **Language Independence**: Works across different languages with focus on low-resource languages
- **Challenge-Adaptive Processing**: Automatically handles:
  - Syntax-based text errors
  - Random space insertion/deletion
  - Connected text (no spaces)
  - Complex semantic structures
  - Multi-lingual input
- **Multiple Tokenization Strategies**: Automatically implements and optimizes:
  - Word-based tokenization
  - Sentence-based tokenization
  - Character-based tokenization
  - Regex-based tokenization
  - Context-sensitive tokenization
  - Frequency-based tokenization
## Performance Across Challenges
### 1. Standard Text Processing
- **Accuracy**: 99%
- **Top Performers**: 
  - Auto-generated basic word tokenizer
  - Adaptive whitespace tokenizer
  - Dynamic n-gram tokenizers
### 2. Connected Text (No Spaces)
- **Accuracy**: 94%
- **Best Solutions**:
  - Auto-generated maximum matching tokenizer
  - Adaptive space normalization dictionary
### 3. Random Space Handling
- **Accuracy**: 84%
- **Features**:
  - Automated statistical model generation
  - Dynamic space normalization
  - Adaptive pattern recognition
### 4. Complex Text Scenarios
- **Accuracy**: 89%
- **Handles**:
  - Informal text
  - Misspellings
  - Multi-lingual content
  - Special characters
## Requirements
- Python 3.x
- Jupyter Notebook

## Detailed Report
For a comprehensive analysis of the system's architecture, methodology, and results, please see my report
