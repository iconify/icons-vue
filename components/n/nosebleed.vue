<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw-3pyb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nosebleed" /></template>
<style>
.hw-3pyb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5c0 3.5-1 6-2.5 7.5c-1 1.5-.5 3.5 1 3.5c1 0 1.5 1 3 1s2-1 3-1c1.5 0 2-2 1-3.5c-1.5-1.5-2.5-4-2.5-7.5m-1.5 14S10 19 10 20a2 2 0 0 0 4 0c0-1-2-3.5-2-3.5Z");
}

</style>
