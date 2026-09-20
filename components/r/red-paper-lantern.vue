<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u2z_debep"/><path class="ehfodky3r"/><radialGradient id="SVGYMf8dbJe" cx="65.103" cy="64.336" r="50.079" gradientTransform="matrix(.7521 0 0 1 14.994 0)" gradientUnits="userSpaceOnUse"><stop offset="0" class="md120d8ra"/><stop offset=".354" class="wb84icb0c"/><stop offset=".749" class="ai1a8abib"/><stop offset="1" class="y0zc0-bpf"/></radialGradient><ellipse fill="url(#SVGYMf8dbJe)" class="f-jy_-efc"/><radialGradient id="SVG088ZR0NS" cx="64" cy="49.182" r="27.681" gradientUnits="userSpaceOnUse"><stop offset=".446" class="ai1a8abib"/><stop offset="1" class="pvdfd6b1d"/></radialGradient><path stroke="url(#SVG088ZR0NS)" class="nxi5uedie"/><radialGradient id="SVGao0JwCNp" cx="63.958" cy="62.678" r="27.651" gradientUnits="userSpaceOnUse"><stop offset=".478" class="ai1a8abib"/><stop offset="1" class="pvdfd6b1d"/></radialGradient><path stroke="url(#SVGao0JwCNp)" class="xmwvsbbjr"/><radialGradient id="SVGpCeyRVuo" cx="63.958" cy="76.161" r="27.651" gradientUnits="userSpaceOnUse"><stop offset=".446" class="ai1a8abib"/><stop offset="1" class="pvdfd6b1d"/></radialGradient><path stroke="url(#SVGpCeyRVuo)" class="ab2axzbdu"/><path class="pzj5oxldt"/><path class="jj5dkyudd"/><path class="vvf_zdbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:red-paper-lantern" /></template>
<style>
.ab2axzbdu {
  fill: none;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M26.03 73.53c3.44 1.16 17.17 5.28 37.9 5.28c20.87 0 34.64-4.18 37.97-5.31");
}

.ai1a8abib {
  stop-color: var(--svg-color--f44336, #f44336);
}

.ehfodky3r {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M77.98 113.76c-11.52 1.13-16.34 1.03-27.97 0c-11.49-1.02-23.95-13.8-23.95-27.03V39.78c0-14.82 12.01-26.83 26.83-26.83H75.1c14.82 0 26.83 12.01 26.83 26.83v46.95c0 13.23-12.62 25.92-23.95 27.03");
}

.f-jy_-efc {
  cx: 63.96px;
  cy: 64.34px;
  rx: 37.66px;
  ry: 50.08px;
}

.jj5dkyudd {
  fill: var(--svg-color--37474f, #37474f);
  d: path("M81.23 12.43c0 1.51-1.09 2.84-2.69 3.27c-2.37.63-6.71 1.29-14.54 1.29s-12.18-.66-14.54-1.29c-1.6-.43-2.69-1.76-2.69-3.27V6.81c0-1.55 1.39-2.81 3.11-2.81h28.24c1.72 0 3.11 1.26 3.11 2.81z");
}

.md120d8ra {
  stop-color: var(--svg-color--fff176, #fff176);
}

.nxi5uedie {
  fill: none;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M26.03 46.57c3.44 1.16 17.17 5.28 37.9 5.28c21.05 0 34.88-4.25 38.05-5.34");
}

.pvdfd6b1d {
  stop-color: var(--svg-color--9b0000, #9b0000);
}

.pzj5oxldt {
  fill: none;
  stroke: var(--svg-color--9b0000, #9b0000);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M33.18 21.58c6.53 1.61 16.25 3.3 30.74 3.3c14.53 0 24.15-1.68 30.67-3.29M26.31 33.18c3.87 1.27 17.42 5.19 37.61 5.19c20.31 0 33.9-3.96 37.68-5.21M26.03 87.01c3.44 1.16 17.17 5.28 37.9 5.28c20.87 0 34.64-4.18 37.97-5.31m-71.2 14.89c6.04 1.65 16.89 3.91 33.22 3.91c16.16 0 27.2-2.51 33.29-4.16");
}

.u2z_debep {
  fill: var(--svg-color--37474f, #37474f);
  d: path("M81.23 119.44c0 1.51-1.09 2.84-2.69 3.27c-2.36.63-6.71 1.29-14.54 1.29s-12.18-.66-14.54-1.29c-1.6-.43-2.69-1.76-2.69-3.27v-5.62c0-1.55 1.39-2.81 3.11-2.81h28.24c1.72 0 3.11 1.26 3.11 2.81z");
}

.vvf_zdbac {
  fill: var(--svg-color--2f7889, #2f7889);
  d: path("M49.77 5.75c.95.22 2.58.46 5.21.49c.5.01.9.38.9.83l.01 7.47c0 .48-.45.85-.98.83c-3.13-.11-4.96-.76-5.77-1.13a.82.82 0 0 1-.5-.74V6.56c0-.53.55-.94 1.13-.81");
}

.wb84icb0c {
  stop-color: var(--svg-color--ff9800, #ff9800);
}

.xmwvsbbjr {
  fill: none;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M26.03 60.05c3.44 1.16 17.17 5.28 37.9 5.28c20.87 0 34.64-4.18 37.97-5.31");
}

.y0zc0-bpf {
  stop-color: var(--svg-color--f44336, #f44336);
  stop-opacity: 0;
}

</style>
