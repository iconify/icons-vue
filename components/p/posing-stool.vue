<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw4dbfbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:posing-stool" /></template>
<style>
.mw4dbfbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5a7 2.5 0 1 0 14 0A7 2.5 0 1 0 5 5Zm7 2.5v14m0-6.5l-6.5 6.5M12 15l6.5 6.5");
}

</style>
