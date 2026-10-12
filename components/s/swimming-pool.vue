<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnia7kk8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swimming-pool" /></template>
<style>
.vnia7kk8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 13.75V5.5a2.25 2.25 0 0 0-4.5 0m12 8.25V5.5a2.25 2.25 0 0 0-4.5 0m-3 2.5h7.5m-7.5 3.25h7.5M3 17.25q2.25-1 4.5 0t4.5 0t4.5 0t4.5 0M3 20.5q2.25-1 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
