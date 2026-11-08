ITZKXTEE — KT SIGNATURE EDITION — V4

A new asymmetrical design using satin graphite, sculpted pearl surfaces,
rose metal inlays, and the supplied official KT mark.
All visible labels and documentation are in English.

OBS INSTALLATION
Keep your existing Xbox One Gamepad Viewer Browser source and player URL.
Set the source to 750 × 630. Copy ALL of itzkxtee-obs.css into the OBS
Browser source Custom CSS field, refresh the source, and press a button.
All graphics are embedded; no image hosting is required.

EXTERNAL CSS
Host edit.css and all nine .svgz files together on HTTPS and use Edit CSS URL,
or host the self-contained itzkxtee-obs.css on its own. The SVGZ files contain
plain SVG, as in the original pack: serve as image/svg+xml without a gzip
Content-Encoding header. This package is not published or hosted.

LOCAL PREVIEW
Open preview.html for Idle, Active inputs, Demo, Disconnected, and Live controller.
Z/X/C/V = A/B/X/Y; arrows = D-pad; Q/E = LB/RB; R/T = LT/RT.
Click or touch the controller controls to preview them manually.
Live input requires a Gamepad API browser on localhost or HTTPS.
If Python is installed, run from this folder:
  python -m http.server 8765 --bind 127.0.0.1
Then open http://127.0.0.1:8765/preview.html and press a controller button.
Gamepad Viewer retains its own detection, player selection, and remapping.

FILES
itzkxtee-obs.css: complete OBS skin, including all artwork and logo.
edit.css + *.svgz: external-asset version.
assets/*.svg: editable sources and original-size input atlases.
assets/kt-logo.svg / .png: supplied official mark, unchanged from its export.
Preview*.png / .svg: transparent idle, active, and disconnected previews.
Presentation.png / .svg: full design overview.
Detail.png / .svg: enlarged material and control detail.
CHANGES.md, VALIDATION.md, manifest.json: notes and checks.
LICENSE.txt: original Dracula Theme MIT license, retained unchanged.

REFERENCE
The supplied Trackmania car colors and official KT mark remain the brand
reference. Original reference files have not been modified.
Rights to the KT mark remain with its owner.

V3 REFINEMENTS
Smaller centered KT logo (62 × 58). Pink inlay aligned with the pearl edge
and joined flush to the upper panel. The pearl panel now uses the exact
front-face silhouette, removing the stray dark strip on the outer-left edge.
Refinements.png / .svg shows the close-up before/after comparison.

V4 — SHELL FINISH + XBOX GUIDE LIGHT
Refined pearl lighting, deeper graphite shading, fine satin grain, and
soft molded joins at the palm surfaces. The smaller logo and clean
outer-shell/pink-inlay edges from V3 are preserved.

The actual logo turns hot pink with a soft glow while Xbox / Guide is held,
then returns to white when released. The CSS uses the official GPV
.meta.pressed control, confirmed in the current Xbox One overlay.
Use the Xbox / Guide preview button, hold G, or press/click the logo itself
to preview the effect. Live input follows the Guide event reported by the
browser: an OS or application that intercepts that event can prevent it
from reaching Gamepad Viewer. No physical Xbox button was tested here.

Host assets/kt-logo-pink.svg along with the external-asset version.
The OBS CSS already includes this asset; no separate image is required.
Logo-glow.png compares Idle and Xbox / Guide held. Preview-guide.png
shows the full controller with just the Guide highlight active.
