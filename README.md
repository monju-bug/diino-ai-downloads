# Diino AI downloads

Optional files that Diino AI downloads when someone turns on voice typing. They are not part of Diino AI itself.

## Whisper (voice typing)

Whisper is a separate open-source project. Diino AI does not own it.

- **Model:** Whisper by OpenAI (MIT License), https://github.com/openai/whisper. Diino AI downloads the model file directly from the whisper.cpp Hugging Face page.
- **Engine:** whisper.cpp by Georgi Gerganov and contributors (MIT License), https://github.com/ggml-org/whisper.cpp.

The `speech-v1` release has an unmodified build of `whisper-cli` from whisper.cpp for Apple Silicon Macs (macOS 13 or newer), because whisper.cpp does not publish a ready-made Mac program. Its licence and notice are included next to it.
