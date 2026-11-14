<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrvebeall"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tide-low" /></template>
<style>
.hrvebeall {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14C7 9 17 9 21.5 14M12 2.5V7M9.5 4.5L12 7l2.5-2.5M2.5 18q2.375-2 4.75 0T12 18t4.75 0t4.75 0");
}

</style>
