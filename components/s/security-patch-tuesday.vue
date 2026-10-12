<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="yz1t3jbri"/><path class="yfxbac5_d"/><path class="e8hdfoncf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-patch-tuesday" /></template>
<style>
.e8hdfoncf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yfxbac5_d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.75v3m9-3v3M2.75 9h18.5m-5.89 3l-.36-.36q-1.06-1.06-2.12 0l-4.24 4.24q-1.06 1.06 0 2.12l.36.36q1.06 1.06 2.12 0l4.24-4.24q1.06-1.06 0-2.12");
}

.yz1t3jbri {
  width: 18.5px;
  height: 17px;
  x: 2.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

</style>
