<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8jam8bkc"/><path class="x-1nmhram"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:qr-pairing" /></template>
<style>
.d8jam8bkc {
  d: path("M4.75 3h3A1.75 1.75 0 0 1 9.5 4.75v3A1.75 1.75 0 0 1 7.75 9.5h-3A1.75 1.75 0 0 1 3 7.75v-3A1.75 1.75 0 0 1 4.75 3m11.5 0h3A1.75 1.75 0 0 1 21 4.75v3a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 16.25 3M4.75 14.5h3a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 7.75 21h-3A1.75 1.75 0 0 1 3 19.25v-3a1.75 1.75 0 0 1 1.75-1.75m1.5-8.25h.01m11.49 0h.01M6.25 17.75h.01m9.149 1.573l1.414-1.414a1.25 1.25 0 0 1 1.768 0a1.25 1.25 0 0 1 0 1.768l-1.414 1.414a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-1nmhram {
  d: path("m17.909 16.823l1.414-1.414a1.25 1.25 0 0 1 1.768 0a1.25 1.25 0 0 1 0 1.768l-1.414 1.414a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768");
}

</style>
