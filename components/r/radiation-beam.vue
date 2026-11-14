<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-wibacbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radiation-beam" /></template>
<style>
.i-wibacbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.5h11.5A2.25 2.25 0 0 1 20 4.75A2.25 2.25 0 0 1 17.75 7H6.25A2.25 2.25 0 0 1 4 4.75A2.25 2.25 0 0 1 6.25 2.5M10.5 7h3a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1a1 1 0 0 1 1-1m0 2l-1.75 5.75M13.5 9l1.75 5.75M12 15v4.5m-2.25-2.25h4.5M3 21.5h18");
}

</style>
