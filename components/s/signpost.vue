<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzq10wytn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:signpost" /></template>
<style>
.pzq10wytn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4H16.5q1 0 1.71.71l1.33 1.33q.71.71 0 1.42l-1.33 1.33q-.71.71-1.71.71H6.25q-1 0-1-1V5q0-1 1-1m1.25 8h10.25q1 0 1 1v3.5q0 1-1 1H7.5q-1 0-1.71-.71l-1.33-1.33q-.71-.71 0-1.42l1.33-1.33Q6.5 12 7.5 12M12 9.5V12m0 5.5v3.75");
}

</style>
