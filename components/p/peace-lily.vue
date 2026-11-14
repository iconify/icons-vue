<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lttzcbb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:peace-lily" /></template>
<style>
.lttzcbb1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15c-5-2-4.5-9 0-12.5C16.5 6 17 13 12 15Zm0 0v6.5m0-9.5V7.5m0 14C7 21 4 17 4 13c4 .5 7 4 8 8.5Zm0 0c5-.5 8-4.5 8-8.5c-4 .5-7 4-8 8.5Z");
}

</style>
