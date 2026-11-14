<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5335zbgf"/><path class="ja5f5mwdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-guidance-sign" /></template>
<style>
.b5335zbgf {
  d: path("M5.125 3h10.214a2.63 2.63 0 0 1 1.942.859l2.614 2.875a2.625 2.625 0 0 1 0 3.532l-2.614 2.875a2.63 2.63 0 0 1-1.942.859H5.125A2.625 2.625 0 0 1 2.5 11.375v-5.75A2.625 2.625 0 0 1 5.125 3M6 14v7.5M9 6v5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja5f5mwdu {
  d: path("M9 6h2.5a2 2 0 0 1 0 4H9");
}

</style>
