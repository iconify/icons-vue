<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGGlZ4Zc7X" cx="64" cy="64" r="75.48" fx="64" fy="64" gradientUnits="userSpaceOnUse"><stop offset=".56" class="qq29bpbzz"/><stop offset=".69" class="zy_6j8ems"/><stop offset=".82" class="y589grvmz"/></radialGradient><radialGradient id="SVGjvLFDeSL" cx="66.15" cy="100.92" r="66.57" fx="66.15" fy="100.92" gradientTransform="matrix(1 0 0 1.09 0 -8.84)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="qq29bpbzz"/><stop offset=".85" class="zy_6j8ems"/><stop offset="1" class="y589grvmz"/></radialGradient><radialGradient id="SVG6aoXscYt" cx="-224.66" cy="-1165.29" r="15.02" fx="-224.66" fy="-1165.29" gradientTransform="matrix(1.01715 .1622 .23601 -.71171 586.48 -729.97)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ff0r6ob3r"/><stop offset=".14" class="i2k0snbeu"/><stop offset=".4" class="o9-1djsua"/><stop offset=".78" class="hkvf__bwf"/><stop offset="1" class="fxtnvdbnu"/></radialGradient><radialGradient id="SVGpWZ5hBzz" cx="-611.05" cy="-1087.16" r="15.02" fx="-611.05" fy="-1087.16" gradientTransform="matrix(-1.01715 .1622 -.23601 -.71171 -833.08 -611.74)" href="#SVG6aoXscYt"/></defs><circle class="m89ag_bsj"/><path fill="url(#SVGGlZ4Zc7X)" class="y-8_w3bgg"/><circle fill="url(#SVGjvLFDeSL)" class="jb___pbqc"/><g class="wj4kgr0on"><path class="g55kn1bwk"/><g class="qp89kubki"><ellipse class="dcaa36cpo"/><path class="lz1yo0bnx"/><ellipse class="z4_3iu64r"/><path class="u_e9wb9ey"/></g><path fill="url(#SVG6aoXscYt)" class="yl19-fb0u"/><path fill="url(#SVGpWZ5hBzz)" class="mhsi4qb6f"/><path class="yqjczjblm"/><path class="wfogl-beg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sun-with-face" /></template>
<style>
.dcaa36cpo {
  cx: 46.77px;
  cy: 54.79px;
  rx: 5.25px;
  ry: 5.67px;
}

.ff0r6ob3r {
  stop-color: var(--svg-color--ffe263, #ffe263);
  stop-opacity: 0.8;
}

.fxtnvdbnu {
  stop-color: var(--svg-color--ffe263, #ffe263);
  stop-opacity: 0;
}

.g55kn1bwk {
  fill: var(--svg-color--de7321, #de7321);
  d: path("M57.84 70.52c-1.39-1.42-.11-2.17 1.42-1.74c1.93.54 5.01.28 5.81-1.3c1.52-3.04-.38-4.76-2.74-10.02c-2.46-5.5.63-11.49 4.2-11.8c2.86-.24 1.91 1.12 1.01 1.7c-1.75 1.14-3.6 4.93-.77 9.17c4.82 7.21 4.82 10.62 2.33 14.06c-1.62 2.23-7.36 3.95-11.27-.06Z");
}

.hkvf__bwf {
  stop-color: var(--svg-color--rgba-255-226-99-2, rgba(255, 226, 99, .2));
  stop-opacity: 0.2;
}

.i2k0snbeu {
  stop-color: var(--svg-color--rgba-255-226-99-72, rgba(255, 226, 99, .72));
  stop-opacity: 0.72;
}

.jb___pbqc {
  cx: 64px;
  cy: 64px;
  r: 42.46px;
}

.lz1yo0bnx {
  d: path("M46.77 48.52c-5.88 0-8.37 5.08-8.37 6.8c0 .91 1.11.95 1.63.07c.52-.89 2.54-3.33 6.74-3.33s6.22 2.44 6.74 3.33s1.63.84 1.63-.07c0-1.71-2.5-6.8-8.37-6.8");
}

.m89ag_bsj {
  cx: 63.57px;
  cy: 64px;
  r: 42.46px;
  fill: var(--svg-color--ffb300, #ffb300);
}

.mhsi4qb6f {
  d: path("M55.85 69.92c-.69 3.69-6.23 5.96-12.38 5.07c-6.15-.88-10.58-4.6-9.89-8.28c.69-3.69 6.23-5.96 12.38-5.07c6.15.88 10.58 4.59 9.89 8.28");
}

.o9-1djsua {
  stop-color: var(--svg-color--rgba-255-226-99-52, rgba(255, 226, 99, .52));
  stop-opacity: 0.52;
}

.qp89kubki {
  fill: var(--svg-color--5d4037, #5d4037);
}

.qq29bpbzz {
  stop-color: var(--svg-color--ffb604, #ffb604);
}

.u_e9wb9ey {
  d: path("M81.23 48.52c-5.88 0-8.37 5.08-8.37 6.8c0 .91 1.11.95 1.63.07c.52-.89 2.54-3.33 6.74-3.33s6.22 2.44 6.74 3.33s1.63.84 1.63-.07c0-1.71-2.5-6.8-8.37-6.8");
}

.wfogl-beg {
  fill: var(--svg-color--de7321, #de7321);
  d: path("M62.6 86.91c-1.63.64-1.37 2.45.35 2.81c2.16.45 3.81.05 5.42-.92c1.6-.97 3.35-2.75 2.58-4.04c-.44-.94-2.01.43-3.99 1.11s-3.03.51-4.36 1.03Z");
  opacity: var(--svg-opacity--0-68, 0.68);
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.y-8_w3bgg {
  d: path("M126.99 80.89L108.1 64.12l.06-.3L127 47.13l-24.83-5.09l-.07-.12l8-24.05l-24.03 8.02l-.12-.08L80.86.99L64 20.02h-.02L47.11 1.01l-5.08 24.88l-.06.03l-24.07-8.04l8 24.05s-.07.09-.11.13L1.01 47.11l19 16.87v.06L1 80.86l24.89 5.11l.02.04l-8.02 24.11l24.05-8.03l.1.08L47.13 127l16.84-19.01h.05l16.87 19l5.07-24.86l.07-.04l24.09 8.02l-8.02-24.03l.07-.12l24.81-5.06Z");
}

.y589grvmz {
  stop-color: var(--svg-color--fdd835, #fdd835);
}

.yl19-fb0u {
  d: path("M72.15 69.92c.69 3.69 6.23 5.96 12.38 5.07c6.15-.88 10.58-4.6 9.89-8.28c-.69-3.69-6.23-5.96-12.38-5.07c-6.15.88-10.58 4.59-9.89 8.28");
}

.yqjczjblm {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("m78.72 75.7l-.11-.06c-.55-.33-1.28-.27-1.76.15c-1.44 1.23-7.41 3.5-12.85 3.61c-5.44-.11-11.41-2.38-12.85-3.61c-.49-.41-1.2-.49-1.76-.15l-.11.06c-.7.42-.83 1.28-.34 1.91c1.89 2.37 6.9 5.93 15.05 6.04c8.15-.11 13.15-3.68 15.05-6.04c.51-.62.38-1.49-.32-1.91");
}

.z4_3iu64r {
  cx: 81.23px;
  cy: 54.79px;
  rx: 5.25px;
  ry: 5.67px;
}

.zy_6j8ems {
  stop-color: var(--svg-color--fec51a, #fec51a);
}

</style>
