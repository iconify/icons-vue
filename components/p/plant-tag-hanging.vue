<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ndtzg3boz"/><path class="hwur48vbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-tag-hanging" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwur48vbb {
  d: path("M12 9.25C12 6 13.5 3.5 15.5 2.5M9.5 18c0-3.5 2.5-5.5 5-5.5c0 3.5-2.5 5.5-5 5.5");
}

.ndtzg3boz {
  d: path("M6.5 9L12 5.5L17.5 9v11a1.5 1.5 0 0 1-1.5 1.5H8A1.5 1.5 0 0 1 6.5 20Zm5.5.25h.01");
}

</style>
