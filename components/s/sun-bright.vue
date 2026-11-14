<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3aubtb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sun-bright" /></template>
<style>
.l3aubtb0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M12 5.75V2.5m0 15.75v3.25M5.75 12H2.5m15.75 0h3.25m-14-4.5L5.25 5.25M16.5 7.5l2.25-2.25M7.5 16.5l-2.25 2.25M16.5 16.5l2.25 2.25");
}

</style>
