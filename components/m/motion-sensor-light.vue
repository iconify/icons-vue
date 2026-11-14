<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2iax_b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:motion-sensor-light" /></template>
<style>
.h2iax_b0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4v4m-5.5 5.5a5.5 5.5 0 0 1 11 0Zm3.5 0a2 2 0 0 0 4 0m5.75-2.25a4.5 4.5 0 0 1 0 6.5m2-8.5a7.5 7.5 0 0 1 0 10.5");
}

</style>
