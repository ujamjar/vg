v0.8.2 2015-08-14 Cambridge (UK)
--------------------------------

- Add `Vgr_cairo` module. A Cairo backend contributed by Arthur Wendling.
- `-safe-string` support. In the public API this only affects users of
  stored `Manual` rendering destination: `Vg.Vgr.Manual.dst` now takes
  a `bytes` value instead of a `string`.


v0.8.1 2014-08-23 Cambridge (UK)
--------------------------------

- Use package builder topkg for distribution.
- Fix build and installation glitches. Thanks to Philippe Veber and
  Grégoire Lionnet for the reports.
- Gg 0.9.0 compatibility.
- Add `Vgr_htmlc.screen_resolution` value.
- `Vgr_htmlc.target` default value for `resolution` argument is now the
  screen resolution rather than 300ppi.
- `Vgr_htmlc.target` add a `resize` optional argument. When set to
  `false` the canvas size is kept intact and doesn't resize according
  to renderable sizes.

v0.8.0 2013-09-24 Lausanne
--------------------------

First release.
Sponsored by Citrix Systems R&D and OCaml Labs.
