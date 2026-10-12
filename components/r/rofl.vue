<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lscd8kr5m"/><path class="zkkb--b5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rofl" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lscd8kr5m {
  cx: 14.25px;
  cy: 13.5px;
  r: 7px;
}

.zkkb--b5r {
  d: path("M11.56 10.66a1.2 1.2 0 0 1 2.11.77m2.35.85a1.2 1.2 0 0 1 2.12.77m-7.37.51l6.11 2.23a3.25 2.75 20 0 1-6.11-2.23M4.4 5.25C5.25 6.5 5.8 7.3 5.8 8A1.4 1.4 0 0 1 3 8c0-.7.55-1.5 1.4-2.75");
}

</style>
