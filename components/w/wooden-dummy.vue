<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtcubr3pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wooden-dummy" /></template>
<style>
.mtcubr3pm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5zA2.5 2.5 0 0 1 14.5 5v14a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 19V5A2.5 2.5 0 0 1 12 2.5m4 2h3A1.5 1.5 0 0 1 20.5 6A1.5 1.5 0 0 1 19 7.5h-3A1.5 1.5 0 0 1 14.5 6A1.5 1.5 0 0 1 16 4.5M9.5 13L4 11m10.5 2l5.5-2");
}

</style>
