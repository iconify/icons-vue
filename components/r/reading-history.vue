<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-vfopat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reading-history" /></template>
<style>
.wm-vfopat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.5c-2-1.5-5.5-2-9-1.5v9.5c3.5-.5 7 0 9 2c2-2 5.5-2.5 9-2V10c-3.5-.5-7 0-9 1.5Zm0 0v10m4.5-15.25a4.5 3.75 0 0 0-9 0M5 4.75l2.5 1.5l2.5-1.5");
}

</style>
