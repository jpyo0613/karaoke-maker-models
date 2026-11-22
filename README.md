# karaoke-maker-models

Mirror of the music separation models an app downloads. Nothing here was trained or changed by us; the files are byte-for-byte copies, renamed. They are in [Releases](../../releases).

| File | What it is | Source | Licence |
|---|---|---|---|
| `vocals.onnx` | UVR-MDX-NET-Voc_FT — takes the vocals out | Ultimate Vocal Remover developers (Anjok07, aufr33 and contributors): [ultimatevocalremovergui](https://github.com/Anjok07/ultimatevocalremovergui), file from [TRvlvr/model_repo](https://github.com/TRvlvr/model_repo/releases/tag/all_public_uvr_models) | "please honor the MIT license by providing credit to UVR and its developers" (their README) |
| `spleeter_vocals.onnx` `spleeter_drums.onnx` `spleeter_bass.onnx` `spleeter_other.onnx` | Spleeter 4 stems (16 kHz, `*.wide.onnx`) | Deezer's [Spleeter](https://github.com/deezer/spleeter), converted to ONNX by [Best-Practice](https://huggingface.co/Best-Practice/spleeter-4stems-onnx) (commit 486643021f18a4d057d282fff1d11b89a30e9887) through [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) | Spleeter: MIT, Copyright (c) 2019-present Deezer SA ([LICENSE-spleeter.txt](LICENSE-spleeter.txt)). Conversion: Apache-2.0 ([LICENSE-apache-2.0.txt](LICENSE-apache-2.0.txt)) |

MDX-Net was developed by Kuielab & Woosung Choi.

## SHA-256

```
534b2070fcc7df514b13ef660dc8cbb328679c2374d04354a5c42bb14ecce111  vocals.onnx
dc1964f146b3e3293c7c14ddb87032467218af3469a5621e9106a8b21032d8ab  spleeter_vocals.onnx
fe76859df85b28f2d0e26c68790957994763db64dc18fd2883550c1a4dab2bac  spleeter_drums.onnx
d5f579b8bb9e0b1d1c758e5c903a6cc2850c0b99189b854b83978b370dbe959b  spleeter_bass.onnx
e097cb54e54989fa530cb290a75897888393aa7f41eab8203e357ce6400dd90e  spleeter_other.onnx
```

If you made one of these models and want something here changed, please open an issue.
