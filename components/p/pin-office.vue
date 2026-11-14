<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="phnhavb1h"/><path class="wyi2sgbkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-office" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.phnhavb1h {
  d: path("M4 19.75v-8A1.75 1.75 0 0 1 5.75 10h2A1.75 1.75 0 0 0 9.5 8.25v-4a1.75 1.75 0 0 1 1.75-1.75h7A1.75 1.75 0 0 1 20 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 19.75M13 6.5v6m3.5-6v6");
}

.wyi2sgbkk {
  d: path("M13 21.5V17h3.5v4.5");
}

</style>
