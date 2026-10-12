<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpbv5_-7t"/><rect class="kkk87lp3o"/><path class="dwavd2bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rocket-firework" /></template>
<style>
.dwavd2bvt {
  d: path("M9 10.5h6m-3 4.25v6.5m-3-4l-1.75 2.5m7.75-2.5l1.75 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkk87lp3o {
  width: 6px;
  height: 7.25px;
  x: 9px;
  y: 7.5px;
  rx: 1px;
}

.zpbv5_-7t {
  d: path("m12.32 3.26l2.36 3.73q.32.51-.28.51H9.6q-.6 0-.28-.51l2.36-3.73q.32-.51.64 0");
}

</style>
