<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bnpmawgqy"/><path class="hp3mh03ed"/><circle class="e8ac64b4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wow-react-sharp" /></template>
<style>
.bnpmawgqy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.3 19.43a8.75 8.75 0 1 0-4.23-4.23l-.67 4.35l-.213 1.281L4.4 20.5Z");
}

.e8ac64b4y {
  cx: 12px;
  cy: 14px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hp3mh03ed {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.25h.01m5.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
