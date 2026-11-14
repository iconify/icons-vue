<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfkoq_ghz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rent-movie" /></template>
<style>
.pfkoq_ghz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.6 16H2.5V3.5h15v9.2M6 3.5V16m6.5-12.5V16m2 2l2.25-2.5h4.75v5h-4.75Zm2.75 0h.01");
}

</style>
