<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzya31w-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snow-stake" /></template>
<style>
.xzya31w-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 20.5V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v16.5m-9.5 0h18M12.5 7H16m-3.5 4H15m-2.5 4H16");
}

</style>
