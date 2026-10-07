RGC Modification Helper — Interactive Demo
===========================================
Open index.html in any browser.

Tabs:
  OVERLAY      — Live HUD. Drag all widgets. Timer counts down in real time.
                 Minimap enemies move. Alert feed cycles live.
  CONFIG       — Toggle widgets, adjust opacity/scale, rebind hotkeys (click key → press new key).
                 Offset map shows patch-resilience design.
  ARCHITECTURE — Decoupled layer diagram: offset map versioned separately from UI.

Key design point:
  When RGC patches, only the offset JSON file changes — the overlay itself doesn't need a rebuild.
  Re-patching is a 5-minute config update, not a code release.

Lucas — available for full implementation on RGC.
