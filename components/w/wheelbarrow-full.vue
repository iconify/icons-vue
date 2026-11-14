<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d5839qmet"/><path class="lumegp62v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wheelbarrow-full" /></template>
<style>
.d5839qmet {
  d: path("M5.5 9.5H21l-3 6H8Z");
}

.lumegp62v {
  d: path("M12.5 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM8 15.5L2.5 11M8 15.5V21M7 9.5c1-3 3.5-3.5 5.5-2.5c2-1.5 6-1 7 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
