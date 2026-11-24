# Venturi Aerator Changelog

## Version 6 (v6-1mmAir-open-ended)

### Key Changes

**Air Gap Optimization:**
- Reduced air injection gap from **5mm to 1mm** (`L_air_off` parameter)
  - Brings air metering closer to the throat area
  - Improves air bubble entrainment efficiency
  - Better bubble size distribution

**Air Metering Orifice:**
- Increased air hole diameter from **0.6mm to 1.0mm** (`D_air_hole` parameter)
  - Provides more precise air flow control
  - Compensates for the reduced gap distance
  - Maintains optimal air injection rates

### Design Specifications

- **Throat Diameter:** 3.25mm (6 throats, 1400 GPH pump)
- **Convergence/Divergence Angle:** 10° both directions
- **Wall Thickness:** 2.4mm for durability
- **Total Length:** ~120.7mm
- **Volume:** ~103.5 cm³

### Rendering

New renders available:
- `V6-1mmAir-iso.png` — Isometric view showing overall geometry
- `V6-1mmAir-top.png` — Top view showing six throats and air metering layout
- `V6-1mmAir-section.png` — Section view showing internal air injection path

### Files

- `Venturi-Aerator-v6-1mmAir-open-ended.sc` — SolidCraft parametric design file
- `parameters-v6-1mmAir-open-ended.csv` — Complete parameter listing

### Comparison to v5

| Parameter | v5 | v6 | Change |
|-----------|----|----|--------|
| Air Gap (`L_air_off`) | 5mm | 1mm | -80% |
| Air Hole Diameter (`D_air_hole`) | 0.6mm | 1.0mm | +67% |
| Design Intent | Standard | Optimized air entrainment | - |

---

## Version 5 (v5-open-ended)

Previous stable release with 5mm air gap and 0.6mm metering orifices.
