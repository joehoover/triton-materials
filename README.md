# triton-materials
This repo is a scratch pad for exploring OpenAI's Triton

# Notes

```
sudo docker pull joehoover/kernl:latest
git clone https://github.com/joehoover/triton-materials.git
sudo docker run --rm -it --gpus all -v $(pwd):/triton-materials joehoover88/kernl:latest
```

## Installation

Lambda Cloud instance had a stale version of Triton. This (issue)[https://github.com/openai/triton/issues/625
] suggested updating with: 

```
pip install --pre -U triton
```

## Useful Links

Triton-lang (introduction)[https://triton-lang.org/master/programming-guide/chapter-1/introduction.html]

https://analyticssteps.com/blogs/openai-triton-programming-language-neural-networks