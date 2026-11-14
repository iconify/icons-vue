<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6_1jwboe"/><path class="lp8v0uw4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:welcome-kit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lp8v0uw4b {
  d: path("M12 18.5c-1.75-1.25-3.25-2.5-3.25-4.25C8.75 13 9.75 12 11 12c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c1.25 0 2.25 1 2.25 2.25c0 1.75-1.5 3-3.25 4.25");
}

.s6_1jwboe {
  d: path("M5.455 8h13.09a1.75 1.75 0 0 1 1.739 1.943l-1.111 10a1.75 1.75 0 0 1-1.739 1.557H6.566a1.75 1.75 0 0 1-1.739-1.557l-1.111-10A1.75 1.75 0 0 1 5.455 8M6 8V5a2.25 2.25 0 0 1 4.5 0v3m3 0V5A2.25 2.25 0 0 1 18 5v3");
}

</style>
