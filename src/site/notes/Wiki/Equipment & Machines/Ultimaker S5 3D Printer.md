---
{"dg-publish":true,"permalink":"/wiki/equipment-and-machines/ultimaker-s5-3-d-printer/","created":"2026-01-27T09:34:25.140+00:00","updated":"2026-01-27T14:01:51.565+00:00"}
---


## 1. Before You Start

**What you need**

- Ultimaker S5 printer (powered on)
- Filament (PLA recommended for beginners)
- Cura (Ultimaker Cura slicer installed on your computer)
- Clean build plate (glass)

**Good to know**

- The S5 has **dual extrusion** (Print Core 1 & 2)
- Touchscreen controls most actions
- Automatic bed levelling is built-in

---

## 2. Power On & Prepare

1. Turn on the printer using the switch at the back.
2. Wait for the touchscreen to fully load.
3. Make sure the **glass build plate is clean**
    - Use isopropyl alcohol for best adhesion
4. Check that the correct **print cores** are installed
    - Common setup:
        - AA 0.4 (model material)
        - BB 0.4 (support material)

---

## 3. Load Filament

1. On the touchscreen, go to:  
    **Material → Load**
2. Select the material type (e.g. PLA).
3. Insert filament into the feeder until it grabs.
4. Wait until melted filament flows smoothly from the nozzle.
5. Confirm on the screen.

✅ Repeat for the second extruder if using dual materials.

---

## 4. Prepare Your Model in Cura

1. Open **Ultimaker Cura**.
2. Select **Printer: Ultimaker S5**.
3. Import your 3D model (STL/OBJ).
4. Choose settings:
    - **Material:** Match what’s loaded in the printer
    - **Layer Height:**
        - 0.2 mm = good balance of quality & speed
    - **Infill:**
        - 20% is fine for most parts
    - **Supports:** Enable if needed
5. Click **Slice**.

---

## 5. Send the Print to the Printer

You have three options:

- **Network (recommended):** Send directly via Cura
- **USB stick**
- **Ultimaker Digital Factory (cloud)**

Once sent, select the job on the printer touchscreen.

---

## 6. Start Printing

1. Confirm materials and print cores on screen.
2. The printer will:
    - Heat up
    - Auto-level the bed
    - Start printing
3. Watch the **first layer**:
    - It should stick well and look smooth
    - If it lifts, stop the print and clean the plate

---

## 7. During the Print

- You can:
    - Pause
    - Adjust speed
    - Monitor temperatures
- Avoid opening doors or touching the printer while printing

---

## 8. After Printing

1. Let the build plate cool down.
2. Remove the glass plate (optional).
3. Gently remove the print using a spatula.
4. Remove supports if used.

---

## 9. Shutdown & Maintenance (Basic)

- Unload filament if not using the printer for a long time
- Clean the build plate regularly
- Keep firmware up to date

---

## Quick Troubleshooting Tips

- **Print not sticking?**
    - Clean the plate
    - Re-level
    - Use a brim
- **Under-extrusion?**
    - Check filament path
    - Clean nozzle
- **Stringing?**
    - Lower nozzle temperature
    - Enable retraction in Cura

---

## Recommended Beginner Settings (PLA)

- Nozzle: **200–210°C**
- Bed: **60°C**
- Speed: **50–70 mm/s**
