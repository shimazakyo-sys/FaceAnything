# FaceAnything Windows Notes

Additional dependencies required for successful execution under Windows.

Community note: Additional dependencies were required to run FaceAnything successfully on Windows.

## Install missing packages

```bash
pip install moviepy==1.0.3
pip install addict
pip install pycolmap
pip install evo
```

## Optional packages

### Triton

Triton is optional and only affects performance.

### gsplat

gsplat is optional and only required for 3D Gaussian Splat rendering.

## Tested Environment

- Windows 11
- Python 3.11
- PyTorch 2.9.0 + CUDA 12.8
- RTX 4070 Ti SUPER

## Verified Result

Successfully tested:

- FaceAnything initialization
- Checkpoint loading
- DA3-GIANT-1.1 download
- Single image inference
- PLY point cloud export
- Depth map export
- Normal map export
- Canonical map export
- Track export
- Meshlab compatibility verification