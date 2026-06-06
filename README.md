# SabiKo TTS Voice Models

Downloadable voice models for the [SabiKo AAC app](https://www.sabikoaac.app/). These are [Piper](https://github.com/rhasspy/piper) ONNX models used with sherpa-onnx for offline neural text-to-speech.

## Models

Each zip contains the voice model files (`.onnx`, `.onnx.json`, `tokens.txt`) inside a named directory. The app's shared `espeak-ng-data` is bundled separately.

### English

| Model | Quality | Size |
|-------|---------|------|
| `vits-piper-en_US-kristin-medium` | Medium | 56 MB |
| `vits-piper-en_US-ryan-medium` | Medium | 56 MB |
| `vits-piper-en_US-lessac-high` | High | 101 MB |
| `vits-piper-en_US-libritts_r-medium` | Medium | 69 MB |

### Spanish

| Model | Quality | Size |
|-------|---------|------|
| `vits-piper-es_MX-claude-high` | High | 56 MB |
| `vits-piper-es_ES-davefx-medium` | Medium | 56 MB |
| `vits-piper-es_ES-sharvard-medium` | Medium | 68 MB |
| `vits-piper-es_MX-ald-medium` | Medium | 56 MB |

### French

| Model | Quality | Size |
|-------|---------|------|
| `vits-piper-fr_FR-siwis-medium` | Medium | 56 MB |
| `vits-piper-fr_FR-tom-medium` | Medium | 56 MB |
| `vits-piper-fr_FR-upmc-medium` | Medium | 68 MB |

### German

| Model | Quality | Size |
|-------|---------|------|
| `vits-piper-de_DE-thorsten-high` | High | 101 MB |
| `vits-piper-de_DE-thorsten-medium` | Medium | 56 MB |
| `vits-piper-de_DE-thorsten_emotional-medium` | Medium | 68 MB |

### Portuguese (Brazilian)

| Model | Quality | Size |
|-------|---------|------|
| `vits-piper-pt_BR-faber-medium` | Medium | 56 MB |
| `vits-piper-pt_BR-cadu-medium` | Medium | 56 MB |
| `vits-piper-pt_BR-jeff-medium` | Medium | 56 MB |

### Vietnamese

| Model | Quality | Size |
|-------|---------|------|
| `vits-piper-vi_VN-vais1000-medium` | Medium | 56 MB |

## Usage

These models are downloaded on demand by the SabiKo app. The default voice (Amy / `en_US-amy-medium`) is bundled with the app.

To publish: create a GitHub Release tagged `v1` and attach all zip files as release assets.

## License

Voice models are from the [Piper](https://github.com/rhasspy/piper) project. See individual MODEL_CARD files for licensing details.
