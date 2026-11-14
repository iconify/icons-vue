<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehrnfxbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traction-control-off" /></template>
<style>
.ehrnfxbuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.54 11.5H5.5V9.4m2.453-5.359c.281-.488.713-.791 1.297-.791h5.5c.75 0 1.25.5 1.5 1.25L17.5 8c.75.25 1 .75 1 1.25v2.25h-3.06M8 21q2.25-1.875 0-3.75t0-3.75m8 7.5q.308-.257.533-.514M3.5 3.5l17 17");
}

</style>
