<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">


</head>
<body>

<h1>Small 7 Segment LCD EDA Files</h1>
<p>Footprints and symbols for the common <strong>3-digit 7-segment glass LCDs</strong> found on Aliexpress, LCSC, Taobao, and Amazon (usually sold as "3-digit LCD module" with no part number). Designed for use with Holtek HT1621/HT1621B LCD controllers.</p>

<img width="3024" height="4032" alt="Segment_LCD_Dual_3_Digit" src="https://github.com/user-attachments/assets/8deb4d46-a654-4ed1-9ae5-d9287bcc10a4" />

<h2>Overview</h2>
<p>These tiny glass LCDs are everywhere — $0.30 each in 10-packs — but no manufacturer provides an EDA footprint. This library fixes that. It includes a 3D STEP file & Fusion360 / Eagle .lbr matching the LCD</p>

<div class="note"><strong>Important:</strong> These are static LCDs, not LEDs. They need AC drive (32-128Hz). Driving with DC will damage the glass. Always use an LCD driver IC.</div>

<h2>What's Included</h2>
<ul>
 <li><code>Tiny_7_seg_LCD.lbr</code> – Fusion 360 / Eagle</li>
 <li><code>TINY_7_SEG_LCD.step</code> – STEP File</li>

</ul>

<h2>Specs</h2>
<ul>
 <li>Glass: 22.4 × 12.6 × 1.1 mm</li>
 <li>Pitch: 1.27 mm, 12 pads (6+6)</li>
 <li>Viewing area: 3× 7-seg digits with DP</li>
 <li>Drive: 1/3 bias, 1/4 duty typical</li>
 <li>Voltage: 2.4-3.3V (VLCD)</li>
</ul>

<h2>Example Board</h2>
<p>The photo shows an example board: two LCDs, HT1621B (LQFP-48), 0.1µF (C1) and 1µF (C2), 10k pullup on CS (R1), and a 7-pin header for MCU connection.</p>



</body>
</html>
