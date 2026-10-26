# Hobie 14 Wing Bench

A wing bench for a Hobie 14 Turbo catamaran, designed and built by Grant O'Brien.
It is a work in progress, not a finished product.

## Files

- `HobieWingBench.stl` — the original CAD geometry, in ASCII STL format (4,096 facets, watertight).
- `HobieWingBench.gltf` — the same geometry as a glTF file with an embedded buffer, for use with Google's model-viewer. It carries a single brushed-aluminum material (silver, fully metallic, roughness 0.35), matching the planned 6061-T6 aluminum build.

## Model

As-modeled extents are about 74.9 long, 21.3 wide, and 11.5 high, in the model's own units. In the glTF file the length runs along X and height along Y, so the bench sits horizontal when viewed.

## Viewing it in 3D

With Google's model-viewer:

```html
<model-viewer src="HobieWingBench.gltf" alt="Aluminum wing bench for a Hobie 14 Turbo catamaran"
  camera-controls auto-rotate environment-image="neutral" shadow-intensity="1">
</model-viewer>
```

## Status

Designed in OpenSCAD and in the process of being built. Dimensions, mounts, and finish may still change.
