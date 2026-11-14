<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eztxrab2o"/><path class="ufhpgbcsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:room-divider-screen" /></template>
<style>
.eztxrab2o {
  d: path("M3 18.5V4l6 2l6-2l6 2v14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ufhpgbcsi {
  d: path("m3 16l6 2l6-2l6 2M9 6v14.5M15 4v14.5");
}

</style>
