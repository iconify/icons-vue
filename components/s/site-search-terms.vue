<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tfb763bqy"/><path class="q6ztswb0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:site-search-terms" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6ztswb0r {
  d: path("M14 11.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m3.75 1.5L19 14.25");
}

.tfb763bqy {
  d: path("M7 7h10a5 5 0 0 1 5 5a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5a5 5 0 0 1 5-5m-1.5 5h2m2 0H12");
}

</style>
