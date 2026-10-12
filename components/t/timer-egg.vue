<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0da-j-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timer-egg" /></template>
<style>
.ys0da-j-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3.6 0 6.75 5.25 6.75 10.5a6.75 6.75 0 0 1-13.5 0C5.25 8 8.4 2.75 12 2.75m-6.4 9h12.8m-6.4-5v2M8.75 15v1.25M12 15v2.25M15.25 15v1.25");
}

</style>
