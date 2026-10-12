<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="irex6lbbg"/><path class="t_xiffbpf"/><rect class="v3l1rcbek"/><path class="eeils9ble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-presenting" /></template>
<style>
.eeils9ble {
  d: path("m12.75 8.25l2-2l1.5 1.5l2.5-2.5m-3 5.5v10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irex6lbbg {
  cx: 5.5px;
  cy: 6.25px;
  r: 2px;
}

.t_xiffbpf {
  d: path("M5.5 10.75v5m-1.75 5.5l1.75-5.5l1.75 5.5M5.5 12l2.75-2");
}

.v3l1rcbek {
  width: 11px;
  height: 8px;
  x: 10.25px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
