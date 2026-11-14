<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vcnxo6b9g"/><path class="sgca-f99r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smoothie-cup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sgca-f99r {
  d: path("M7.25 8.5h9.5A1.25 1.25 0 0 1 18 9.75A1.25 1.25 0 0 1 16.75 11h-9.5A1.25 1.25 0 0 1 6 9.75A1.25 1.25 0 0 1 7.25 8.5m.25 0c0-2.5 2-4 4.5-4s4.5 1.5 4.5 4m-3.25-3.75l2.25-2.5");
}

.vcnxo6b9g {
  d: path("M8.934 11h6.132a1.75 1.75 0 0 1 1.742 1.924l-.65 6.5A1.75 1.75 0 0 1 14.416 21H9.584a1.75 1.75 0 0 1-1.742-1.576l-.65-6.5A1.75 1.75 0 0 1 8.934 11");
}

</style>
