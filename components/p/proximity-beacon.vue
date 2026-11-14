<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd3mqzgqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:proximity-beacon" /></template>
<style>
.yd3mqzgqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5V21m0-12h.01m2.74-2.75a4 4 0 0 1 0 5.5m-5.5-5.5a4 4 0 0 0 0 5.5m8-8a7.5 7.5 0 0 1 0 10.5M6.75 3.75a7.5 7.5 0 0 0 0 10.5");
}

</style>
