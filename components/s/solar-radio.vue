<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e49tywbax"/><path class="lggodsbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-radio" /></template>
<style>
.e49tywbax {
  d: path("M6.5 10h11a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-4A3.5 3.5 0 0 1 6.5 10m-1 0l-2-6.5M12 6h6a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 18 10h-6a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 12 6m3 0v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lggodsbkh {
  d: path("M12.75 15.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6 15.5h3.5");
}

</style>
