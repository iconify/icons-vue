<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqqy_bc_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-blend" /></template>
<style>
.qqqy_bc_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12L3 4C3 3.4477 3.4477 3 4 3L12 3M7 16L7 10C7 8.3431 8.3431 7 10 7L16 7M16 11C18.7614 11 21 13.2386 21 16C21 18.7614 18.7614 21 16 21C13.2386 21 11 18.7614 11 16C11 13.2386 13.2386 11 16 11Z");
}

</style>
