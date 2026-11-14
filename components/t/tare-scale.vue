<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8d2p22ma"/><path class="gm7bwvbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tare-scale" /></template>
<style>
.c8d2p22ma {
  d: path("M5 7.5h14L20.5 21h-17Zm-.5-3h15m-7.5 0v3");
}

.gm7bwvbra {
  d: path("M8 14.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0v-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
