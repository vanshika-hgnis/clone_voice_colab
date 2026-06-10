# clone_voice_colab
Clone voice by uploading video or audio

# How to use 

How to  use it (the cells are labeled 1–7, top to bottom):

- Set Runtime ▸ T4 GPU, then run cell 1 (install).
- Cell 2 — upload the speaker video/audio. It strips to clean mono audio and tells you the duration.
- Cell 3 — the greeting template ({} जी नमस्कार) and MODE='auto'.
- Cell 4 — auto-decides: 4+ min of clean speech → fine-tune; less → zero-shot.
- Cell 5 — fine-tunes (only in Accurate mode; ~15–40 min on the free GPU).
- Cell 6 — plays a sample so they judge quality before committing.
- Cell 7 — upload your Excel → it speaks every name → downloads cloned_voice_clips.zip, files named {Name}_{Mobile}.wav.
