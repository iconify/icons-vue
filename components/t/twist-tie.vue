<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j9s8sgali"/><path class="v-9oxlbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:twist-tie" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9s8sgali {
  d: path("M10.5 12c-5.5 1-7 4-7 6.5c0 2 1.5 3 3.5 3h10c2 0 3.5-1 3.5-3c0-2.5-1.5-5.5-7-6.5m-3-2.5l-2-4h7l-2 4m-2.75 0h2.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 13.25 12h-2.5a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25");
}

.v-9oxlbsp {
  d: path("M14.5 10.75c2 0 3-1.5 2.25-2.5c-.5-.5-1.25-.25-1.25.5m-6 2c-2 0-3-1.5-2.25-2.5c.5-.5 1.25-.25 1.25.5");
}

</style>
