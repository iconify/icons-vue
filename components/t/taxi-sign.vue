<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mafkjmbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taxi-sign" /></template>
<style>
.mafkjmbbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7.5h6.5q1.25 0 1.46 1.23l.83 4.79q.21 1.23-1.04 1.23h-9q-1.25 0-1.04-1.23l.83-4.79Q7.5 7.5 8.75 7.5m-2 4h10.5m-7.75 0v3.25M12 11.5v3.25m2.5-3.25v3.25m-11 5.75c2-3.5 15-3.5 17 0");
}

</style>
