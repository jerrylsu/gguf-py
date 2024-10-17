# Release

- 2024.10.16: [GOT-OCR2_0-716M-BF16-GGUF](https://huggingface.co/Jerry666/GOT-OCR2_0-716M-BF16-GGUF)

# Description

This is a Python package for writing binary files in the GGUF based on llama_cpp.

# Usage

`
python convert_hf_to_gguf.py --outtype bf16 --model ~/GOT-OCR2_0 --outfile ~/output/GOT-OCR2_0-GGUF
`

# Adding Supported Model

[GOT_OCR2](https://huggingface.co/stepfun-ai/GOT-OCR2_0)

Continue...

# References

[llama.cpp](https://github.com/ggerganov/llama.cpp): LLM inference in C/C++.

[GOT-OCR2.0](https://github.com/Ucas-HaoranWei/GOT-OCR2.0): Official code implementation of General OCR Theory: Towards OCR-2.0 via a Unified End-to-end Model.