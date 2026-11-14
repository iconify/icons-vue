<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k3ue1xdmu"/><path class="hlfjavb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-alarm" /></template>
<style>
.hlfjavb5j {
  d: path("M10 9.5v-2c0-1.25.9-2.25 2-2.25s2 1 2 2.25v2m-4.75 0h5.5m-2.75 3v5m0 0l-2.5 3.75h5z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3ue1xdmu {
  d: path("M9 2.5h6A3.5 3.5 0 0 1 18.5 6v3a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 9V6A3.5 3.5 0 0 1 9 2.5");
}

</style>
