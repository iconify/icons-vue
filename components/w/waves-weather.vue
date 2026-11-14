<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klduf9b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waves-weather" /></template>
<style>
.klduf9b6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0M3 12q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0M3 17.5q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
