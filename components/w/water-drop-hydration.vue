<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="athqw2bju"/><path class="x_de3nb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-drop-hydration" /></template>
<style>
.athqw2bju {
  d: path("M10.875 8h2.25a4.375 4.375 0 0 1 4.375 4.375v4.75a4.375 4.375 0 0 1-4.375 4.375h-2.25A4.375 4.375 0 0 1 6.5 17.125v-4.75A4.375 4.375 0 0 1 10.875 8M10 5h4a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 14 8h-4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 10 5m.5 0V2.75H13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_de3nb8r {
  d: path("M12 11.25c1.25 1.5 2.25 2.5 2.25 4c0 1.25-1 2.25-2.25 2.25s-2.25-1-2.25-2.25c0-1.5 1-2.5 2.25-4");
}

</style>
