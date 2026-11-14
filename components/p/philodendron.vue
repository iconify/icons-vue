<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx_353_eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:philodendron" /></template>
<style>
.qx_353_eu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8c-1.5-3.5-7.5-3.5-7.5 2c0 4.5 4 8 7.5 11.5c3.5-3.5 7.5-7 7.5-11.5c0-5.5-6-5.5-7.5-2Zm0 0V2.5M12 8v10.5m0-5.5l-4-3m4 3l4-3");
}

</style>
