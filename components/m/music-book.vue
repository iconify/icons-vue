<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="db2vw0btu"/><path class="wj5lvlbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:music-book" /></template>
<style>
.db2vw0btu {
  d: path("M5 19V5a2.5 2.5 0 0 1 2.5-2.5H19v19H7.5A2.5 2.5 0 0 1 5 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wj5lvlbly {
  d: path("M5 19a2.5 2.5 0 0 1 2.5-2.5H19m-9.75-5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0V6l2.75 1");
}

</style>
