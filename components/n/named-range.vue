<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t2cc_rbhh"/><path class="h2qmzccue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:named-range" /></template>
<style>
.h2qmzccue {
  d: path("M14.5 14.5h3.75l3.5 3.5L18 21.75l-3.5-3.5Zm2.25 2.25h.01");
}

.t2cc_rbhh {
  d: path("M13.3 21H3V3h18v10.3M9 3v18m6-18v8.7M3 9h18M3 15h8.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
