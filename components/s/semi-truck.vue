<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ev864wepd"/><path class="rs1wo2mow"/><circle class="f35nbaban"/><path class="nrfpa2b3d"/><circle class="ltvwwkb6z"/><path class="q-9rn4g0x"/><circle class="efb4smbdq"/><path class="z-k1rmdkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:semi-truck" /></template>
<style>
.efb4smbdq {
  cx: 18.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ev864wepd {
  width: 10.5px;
  height: 11px;
  x: 2.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.f35nbaban {
  cx: 5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ltvwwkb6z {
  cx: 11.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrfpa2b3d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 19h.01");
}

.q-9rn4g0x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.75 19h.01");
}

.rs1wo2mow {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 16.75v-7a1 1 0 0 1 1-1h1.85a1 1 0 0 1 .97.76l.5 2.1c.85.3 1.43 1.1 1.43 2v3.14Zm0-4.5h5.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z-k1rmdkw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 19h.01");
}

</style>
