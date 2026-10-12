<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lrv26qbrg"/><rect class="rnp7s23sz"/><path class="k9uo6ihdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:patch-cable" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9uo6ihdg {
  d: path("M6 11.25v3.5c0 3.6 2.7 6.5 6 6.5s6-2.9 6-6.5v-3.5m-12-6v-2.5m12 2.5v-2.5");
}

.lrv26qbrg {
  width: 3.5px;
  height: 6px;
  x: 4.25px;
  y: 5.25px;
  rx: 1px;
}

.rnp7s23sz {
  width: 3.5px;
  height: 6px;
  x: 16.25px;
  y: 5.25px;
  rx: 1px;
}

</style>
