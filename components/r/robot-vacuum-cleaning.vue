<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbegwuccm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:robot-vacuum-cleaning" /></template>
<style>
.nbegwuccm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 8h11a1 1 0 0 1 1 1v5.5a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1ZM13 8V5h4.5v3M5.708 13.725a9.5 9.5 0 0 1 0-3.95m-2.935 4.574a12.5 12.5 0 0 1 0-5.198M2.5 18.5h19");
}

</style>
