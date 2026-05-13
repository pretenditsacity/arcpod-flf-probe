# First-Last-Frame draw_in model comparison (clip_06 image 5)

Goal: image self-builds from blank sepia to the target illustration over ~5s.
End-frame target = `00_target_image.png` (small figure facing purple screen).

## Successful candidates (this probe)

- `anim_05_vidu-q1-start-end.mp4` — Vidu Q1, 130s gen, 2 MB
- `anim_05_vidu-start-end.mp4` — Vidu (non-Q1), 49s gen, 1 MB
- `anim_05_luma-ray2.mp4` — Luma Ray2, 53s gen, 1.6 MB

## Reference (already-tested models)

- `_ref_ltx.mp4` — LTX-13B-distilled (cheap, hallucination-prone)
- `_ref_wan.mp4` — Wan 2.1 (mid, drifts after completion)

## Stream URLs

