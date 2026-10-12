<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="eh67qx3yv"/><path class="ej4_3wbll"/><path class="wgmbweb9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wall-clock" /></template>
<style>
.eh67qx3yv {
  cx: 12px;
  cy: 14px;
  r: 7px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ej4_3wbll {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h.01");
}

.wgmbweb9j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.25 3.75l-2 2m3.5-2l2 2M12 8.25V9.5m5.75 4.5H16.5M12 19.75V18.5M6.25 14H7.5m4.5-2.75V14l2 1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
