<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cbjj__agi"/><path class="agkchzkat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:policy-start-date" /></template>
<style>
.agkchzkat {
  d: path("m16 15l5 3l-5 3Z");
}

.cbjj__agi {
  d: path("M13.2 20.5H3.5V5h17v9.4M8 3v4m8-4v4M3.5 10h17M8 3v4m8-4v4M3.5 9.5h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
