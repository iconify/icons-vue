<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl-l-nspd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-mast" /></template>
<style>
.fl-l-nspd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5v12m-5.5 0l5.5-10l5.5 10M8.75 8a3.5 3.5 0 0 1 1.75-1.75m3 0A3.5 3.5 0 0 1 15.25 8M6 6.75A6.5 6.5 0 0 1 9.25 3.5m5.5 0A6.5 6.5 0 0 1 18 6.75");
}

</style>
