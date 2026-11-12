<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k04p0xb8w"/><path class="s3r8-qbuj"/><path class="f3f0wlo8y"/><circle class="vzs1ah3os"/><path class="f7azv0kip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-perspective-linear" /></template>
<style>
.f3f0wlo8y {
  d: path("M3.04199 21.2697L12.0004 16");
}

.f7azv0kip {
  d: path("M17 13L17 8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k04p0xb8w {
  d: path("M21.1213 21.1213C22 20.2426 22 18.8284 22 16C22 13.1716 22 11.7574 21.1213 10.8787M21.1213 10.8787C20.2426 10 18.8284 10 16 10L8 10C5.17157 10 3.75736 10 2.87868 10.8787C2 11.7574 2 13.1716 2 16C2 18.8284 2 20.2426 2.87868 21.1213C3.75736 22 5.17157 22 8 22H16C18.8284 22 20.2426 22 21.1213 21.1213M21.1213 21.1213V21.1213ZM21.1213 10.8787V10.8787ZM2.87868 10.8787V10.8787ZM2.87868 21.1213V21.1213Z");
}

.s3r8-qbuj {
  d: path("M21.1568 21.0872L2.84277 10.9127");
}

.vzs1ah3os {
  cx: 17px;
  cy: 5px;
  r: 3px;
}

</style>
