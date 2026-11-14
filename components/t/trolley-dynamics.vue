<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lf4whbp7l"/><path class="vnkza2_uo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trolley-dynamics" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf4whbp7l {
  d: path("M5.125 6.25h6.25A2.625 2.625 0 0 1 14 8.875v1.75a2.625 2.625 0 0 1-2.625 2.625h-6.25A2.625 2.625 0 0 1 2.5 10.625v-1.75A2.625 2.625 0 0 1 5.125 6.25");
}

.vnkza2_uo {
  d: path("M2.75 15.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7.25 2h19m-4.75-7.5h4.75M19.25 7.5l2.25 2.25L19.25 12");
}

</style>
