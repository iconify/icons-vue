<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vbptu_bef"/><path class="i-td7prfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snake" /></template>
<style>
.i-td7prfw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.75 5.75h.01");
}

.vbptu_bef {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.38 5.18A5.35 5.35 0 1 0 12 13.6a2.15 2.15 0 1 1-2.03 2.85q-.12-.59-1.69-1.16q-1.56 1.3-1.34 2.2A5.35 5.35 0 1 0 12 10.4a2.15 2.15 0 1 1 1.76-3.38a1.95 1.95 0 0 0 2.62-1.84m.12 3.07l1 1.25m0 0l1.25.25M17.5 9.5l.25 1.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
