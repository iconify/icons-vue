<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t-5u_hbzu"/><path class="j_oswluqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waste-collection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_oswluqf {
  d: path("M5.25 3.5h13.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 18.75 7H5.25A1.75 1.75 0 0 1 3.5 5.25A1.75 1.75 0 0 1 5.25 3.5m.5 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m9 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M12 10v5.5");
}

.t-5u_hbzu {
  d: path("M6.909 7h10.182a1.75 1.75 0 0 1 1.744 1.902l-.696 8a1.75 1.75 0 0 1-1.743 1.598H7.604a1.75 1.75 0 0 1-1.743-1.598l-.696-8A1.75 1.75 0 0 1 6.909 7");
}

</style>
