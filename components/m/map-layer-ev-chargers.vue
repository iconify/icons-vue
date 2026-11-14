<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vq9c9cc2h"/><path class="d6yxgcb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-layer-ev-chargers" /></template>
<style>
.d6yxgcb0a {
  d: path("M10.75 6.5L7.5 12H11l-2.25 5.5M14.5 14h3a2 2 0 0 0 2-2V6L18 4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vq9c9cc2h {
  d: path("M7.5 3H11a3.5 3.5 0 0 1 3.5 3.5v11A3.5 3.5 0 0 1 11 21H7.5A3.5 3.5 0 0 1 4 17.5v-11A3.5 3.5 0 0 1 7.5 3");
}

</style>
