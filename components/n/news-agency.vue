<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sc5lc9t2i"/><path class="p7-ueuhch"/><path class="ucrm0z99i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:news-agency" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7-ueuhch {
  d: path("M14.5 2.5v5h5m-11.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

.sc5lc9t2i {
  d: path("M4.5 4A1.5 1.5 0 0 1 6 2.5h8.5l5 5V20a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20Z");
}

.ucrm0z99i {
  d: path("M10 14.5a2 4.25 0 1 0 4 0a2 4.25 0 1 0-4 0");
}

</style>
