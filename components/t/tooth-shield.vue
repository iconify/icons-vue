<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybk9s37ds"/><path class="wm1z5mb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-shield" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wm1z5mb8j {
  d: path("M12 8c-1-1-2.5-1.25-3.25-.75c-1 .75-1 2.5-.5 3.75s.5 2.5 1 4c.25 1 1 1 1.25 0l.5-2c.25-.75 1.75-.75 2 0l.5 2c.25 1 1 1 1.25 0c.5-1.5.5-2.75 1-4s.5-3-.5-3.75C14.5 6.75 13 7 12 8");
}

.ybk9s37ds {
  d: path("M4 3h16v8c0 5-3.5 8.5-8 10.5c-4.5-2-8-5.5-8-10.5Z");
}

</style>
