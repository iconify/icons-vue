<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ljgkw_qjw"/><path class="k7_it40pu"/><path class="nk5tb1bvs"/><path class="ms1i8-btl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:router-secure" /></template>
<style>
.k7_it40pu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 13V7.5m12.5 5.5V7.5");
}

.ljgkw_qjw {
  width: 18.5px;
  height: 8.25px;
  x: 2.75px;
  y: 13px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.ms1i8-btl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 17.25h4M12 2.75l3 1.1v3c0 2-1.3 3.4-3 4.4c-1.7-1-3-2.4-3-4.4v-3Z");
}

.nk5tb1bvs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 17.25h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
