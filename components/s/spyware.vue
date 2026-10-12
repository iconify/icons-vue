<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="forh_3gyy"/><path class="ubhr-d85f"/><path class="cs185qb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spyware" /></template>
<style>
.cs185qb-c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14h.01");
}

.forh_3gyy {
  width: 18.5px;
  height: 16px;
  x: 2.75px;
  y: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

.ubhr-d85f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8h18.5M6.5 14c1.5-2.25 3.4-3.25 5.5-3.25s4 1 5.5 3.25c-1.5 2.25-3.4 3.25-5.5 3.25s-4-1-5.5-3.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
