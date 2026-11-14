<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wmik5gbjg"/><path class="wrl3evboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-support-stake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmik5gbjg {
  d: path("M18.5 2.5v19m-8 0c0-4-.75-7.5 0-12.5");
}

.wrl3evboa {
  d: path("M10.25 11C7 11 4.5 9.5 4.5 7c3 0 5.5 1.5 5.75 4m.25-2c0-2.5 2-4.5 5-4.5c0 2.5-2 4.5-5 4.5m-1 7a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0");
}

</style>
