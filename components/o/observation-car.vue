<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hi_5hbt7a"/><path class="echwhx8-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:observation-car" /></template>
<style>
.echwhx8-h {
  d: path("M4.25 16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m12 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M2.5 18.25h19");
}

.hi_5hbt7a {
  d: path("M2.5 14.75v-5A1.5 1.5 0 0 1 4 8.25h3.5c1-4.25 8-4.25 9 0H20a1.5 1.5 0 0 1 1.5 1.5v5ZM5 11.5h2.75m2.75 0h3m2.75 0H19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
