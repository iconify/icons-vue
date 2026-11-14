<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypcr7eaig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-strike" /></template>
<style>
.ypcr7eaig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 7.5C16 5.75 14.25 4.75 12 4.75c-2.5 0-4.5 1.25-4.5 3.5c0 4.75 9 2.5 9 7.5c0 2.25-2 3.5-4.5 3.5s-4.25-1-4.75-2.75M12 2.5v2.25m0 14.5v2.25M2.5 12h19");
}

</style>
