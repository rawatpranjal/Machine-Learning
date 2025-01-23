## PDF-Extract-Kit-1.0 Model Repository

This is the model repository corresponding to version 1.0 of PDF-Extract-Kit. For usage, please refer to:

- [PDF-Extract-Kit-1.0](https://github.com/opendatalab/PDF-Extract-Kit)
- [MinerU](https://github.com/opendatalab/MinerU)


### SDK Download

```bash
# First, install the huggingface library using pip:
pip install huggingface_hub
```

```python
# Use the following Python code to download the model using the huggingface SDK:
from huggingface_hub import snapshot_download

snapshot_download(repo_id='opendatalab/pdf-extract-kit-1.0', local_dir='./', max_workers=20)
```

### Git Download
Alternatively, you can use Git to clone the model repository from ModelScope:

```bash
git lfs install
git clone https://huggingface.co/opendatalab/PDF-Extract-Kit-1.0
```

---
license: apache-2.0
---
