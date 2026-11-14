<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exoh6o5hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scuba-tank" /></template>
<style>
.exoh6o5hl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5za4.5 4.5 0 0 1 4.5 4.5v6a4.5 4.5 0 0 1-4.5 4.5A4.5 4.5 0 0 1 7.5 17v-6A4.5 4.5 0 0 1 12 6.5m-1.5 0v-3h3v3m0-1.5H17m-9.5 6h9");
}

</style>
