<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo-jg-5zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spa-facility" /></template>
<style>
.qo-jg-5zn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c2.75 3.25 3.25 7.5 0 13c-3.25-5.5-2.75-9.75 0-13Zm0 13c-4.5 0-8.5-2.5-9.5-7c3 0 5.25 1 6.75 2.5M12 16.5c4.5 0 8.5-2.5 9.5-7c-3 0-5.25 1-6.75 2.5M5 20h14");
}

</style>
