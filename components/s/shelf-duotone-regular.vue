<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asqszxb9j"/><path class="moitg-beq"/><path class="lbllh8b8w"/><path class="qc-1i0btz"/><path class="dd2oi04rr"/><path class="ozi-k-boi"/><path class="n-7t0yb1r"/><path class="rkhcgsbdl"/><path class="vxuzbkitn"/><path class="z1zyir08z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shelf-duotone-regular" /></template>
<style>
.asqszxb9j {
  fill: currentColor;
  d: path("M5.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dd2oi04rr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lbllh8b8w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.moitg-beq {
  fill: currentColor;
  d: path("M14.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.qc-1i0btz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.vxuzbkitn {
  d: path("M5.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z1zyir08z {
  d: path("M14.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
