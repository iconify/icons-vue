<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4tq0obyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-sharp" /></template>
<style>
.k4tq0obyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h10v7c0 .958-.106 1.855-.305 2.695m-1.952 4.048C16.3 18.59 14.279 19.987 12 21c-4.5-2-8-5.5-8-11V3M3 2l19 19");
}

</style>
