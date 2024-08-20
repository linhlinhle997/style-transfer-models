---
title: README
created: '2020-07-13T05:50:38.161Z'
modified: '2020-07-13T07:00:44.840Z'
---

# Neural Style Transfer with Pre-Trained Models

### Pre-Trained Models
- eccv16: `composition_vii.t7`, `la_muse.t7`, `starry_night.t7`, `the_wave.t7`
- instance_norm: `candy.t7`, `featheres.t7`, `la_muse.t7`, `mosaic.t7`, `starry_night.t7`, `the_scream.t7`, `udnie.t7`

### Use
1. Run with image
```markdown
python neural_style_transfer.py --image images/input/*.jpg --model models/instance_norm/starry_night.t7 --output images/output/*.jpg
```
- Run with video stream
```markdown
python neural_style_transfer_video.py --model models/instance_norm/starry_night.t7
```
### Reference
- pyimagesearch: [Neural Style Transfer with OpenCV](https://www.pyimagesearch.com/2018/08/27/neural-style-transfer-with-opencv/)
