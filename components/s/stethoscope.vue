<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ud736cb3r"/><path class="nm1ak_bdh"/><path class="ivxxnh22o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stethoscope" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivxxnh22o {
  d: path("M16 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.nm1ak_bdh {
  d: path("M8.5 12.5v3a4.75 4.75 0 0 0 9.5 0v-1");
}

.ud736cb3r {
  d: path("M4 3.5V8a4.5 4.5 0 0 0 9 0V3.5");
}

</style>
