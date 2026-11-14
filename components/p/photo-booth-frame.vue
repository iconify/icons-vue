<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yukrl4bhq"/><path class="x24jg10ci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:photo-booth-frame" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x24jg10ci {
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.5 8.5c0-2.75 2-3.75 4.5-3.75s4.5 1 4.5 3.75");
}

.yukrl4bhq {
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v7a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 13V6a3.5 3.5 0 0 1 3.5-3.5m3 14v4a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-4");
}

</style>
