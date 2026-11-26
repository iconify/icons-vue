<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5n161xip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-scorpio-two-tone" /></template>
<style>
.y5n161xip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 15L2 6C2 4.3431 3.3431 3 5 3C6.6569 3 8 4.3431 8 6L8 15M8 6C8 4.3431 9.3431 3 11 3C12.6569 3 14 4.3431 14 6L14 14C14 15.6569 15.3431 17 17 17L22 17M18 13L21.8436 16.6368C21.9478 16.7355 22 16.8677 22 17C22 17.1323 21.9478 17.2645 21.8436 17.3632L18 21");
}

</style>
