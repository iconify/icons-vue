<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twlk-z14e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-refill-fountain" /></template>
<style>
.twlk-z14e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5h12V11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2ZM9 13v7.5m-3 0h6m-6.5-11c0-6.5 6.5-7 7-2.75M16 21.5h5V17l-1.25-1.25V14h-2.5v1.75L16 17Z");
}

</style>
