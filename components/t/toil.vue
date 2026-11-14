<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gq3lnsbfz"/><path class="xx-cakmif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toil" /></template>
<style>
.gq3lnsbfz {
  d: path("M21 12a9 9 0 1 1-1.25-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xx-cakmif {
  d: path("M19.75 3.75V7.5H17m-3.75.25a2.75 2.75 0 1 0 3 3M11.5 12.5L8 16");
}

</style>
