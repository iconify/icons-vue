<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tct8x_bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:measure-radiation" /></template>
<style>
.tct8x_bii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.25 9l-3-5.25a9.5 9.5 0 0 1 9.5 0l-3 5.25a3.5 3.5 0 0 0-3.5 0m5.25 3h6a9.5 9.5 0 0 1-4.75 8.25l-3-5.25a3.5 3.5 0 0 0 1.75-3m-8.25 8.25l3-5.25a3.5 3.5 0 0 1-1.75-3h-6a9.5 9.5 0 0 0 4.75 8.25M12 12h.01");
}

</style>
