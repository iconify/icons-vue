<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="n6-bn0bqx"/><circle class="k0a36_yae"/><path class="p6vfrcxbc"/><path class="znlnqjb3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:revenue" /></template>
<style>
.k0a36_yae {
  cx: 12px;
  cy: 15.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n6-bn0bqx {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.p6vfrcxbc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 15.75h.01m10.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.znlnqjb3d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.75v-5m-3 3l3-3l3 3");
}

</style>
