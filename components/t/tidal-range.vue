<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_itudmre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tidal-range" /></template>
<style>
.a_itudmre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4q2.375-2 4.75 0T12 4t4.75 0t4.75 0m-19 16q2.375-2 4.75 0T12 20t4.75 0t4.75 0M12 8v8m-2.5-5.5L12 8l2.5 2.5m-5 3L12 16l2.5-2.5");
}

</style>
