<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z326zhwbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-handset" /></template>
<style>
.z326zhwbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5c0-3 4-5 9-5s9 2 9 5V15a1 1 0 0 1-1 1h-3.5a1 1 0 0 1-1-1v-1.5a11.17 11.17 0 0 0-7 0V15a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
