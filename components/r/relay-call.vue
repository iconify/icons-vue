<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-wqmfblh"/><path class="znkkhg-1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:relay-call" /></template>
<style>
.g-wqmfblh {
  d: path("M5 3.75h2.5L9.25 8l-2 1.25a11 11 0 0 0 5.5 5.5l1.25-2l4.25 1.75V17a2 2 0 0 1-2 2A15 15 0 0 1 3 5.75a2 2 0 0 1 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znkkhg-1c {
  d: path("M14.25 2.75h5a2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2H17L14.75 11V9.25h-.5a2 2 0 0 1-2-2v-2.5a2 2 0 0 1 2-2M15 6h3.5");
}

</style>
