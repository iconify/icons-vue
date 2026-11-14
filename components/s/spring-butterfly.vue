<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1t3_gbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spring-butterfly" /></template>
<style>
.y1t3_gbqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8C9 3 2.75 3 2.75 8c0 3.5 4.25 4.5 9.25 3m0-3c3-5 9.25-5 9.25 0c0 3.5-4.25 4.5-9.25 3m0 3c-4.5-.5-7 1.5-6.75 4S10 20.5 12 17.5m0-3.5c4.5-.5 7 1.5 6.75 4S14 20.5 12 17.5M12 8v9.5");
}

</style>
