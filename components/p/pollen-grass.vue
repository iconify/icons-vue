<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcaim9bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pollen-grass" /></template>
<style>
.xcaim9bqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21h18M8 21q-1-5-3.5-9m7.5 9V10m4 11q1-5 3.5-9M6 8h.01M12 5.5h.01M18 8h.01");
}

</style>
