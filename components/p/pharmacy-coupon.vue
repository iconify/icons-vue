<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bad244bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pharmacy-coupon" /></template>
<style>
.bad244bjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h19v4.25a2.25 2.25 0 0 0 0 4.5v4.25h-19v-4.25a2.25 2.25 0 0 0 0-4.5Zm6.5 10l6-7m-5.75.75h.01m5.49 5.5h.01");
}

</style>
