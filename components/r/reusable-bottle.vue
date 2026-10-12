<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vhx1ijesb"/><path class="vqa2enb-o"/><path class="dvzftex6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reusable-bottle" /></template>
<style>
.dvzftex6n {
  d: path("M9.5 17.75c.2-2.8 1.6-4.4 4.75-5c-.2 2.8-1.6 4.4-4.75 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhx1ijesb {
  width: 6px;
  height: 3.25px;
  x: 9px;
  y: 2.75px;
  rx: 1px;
}

.vqa2enb-o {
  d: path("M9.5 6h5v.5c1.75.75 2.75 2 2.75 3.75v9a2 2 0 0 1-2 2h-6.5a2 2 0 0 1-2-2v-9c0-1.75 1-3 2.75-3.75Z");
}

</style>
