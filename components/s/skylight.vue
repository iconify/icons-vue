<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhxs0nb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skylight" /></template>
<style>
.zhxs0nb6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14L8 11.375m9-4.5l4.25-2.125M8.67 9.29l7.66-3.83q.67-.33.67.42v2q0 .75-.67 1.08l-7.66 3.83q-.67.34-.67-.41v-2q0-.75.67-1.09m3.83-1.915v3.5m-3 4.625v4m3.5-5.75v4M16.5 12v4");
}

</style>
