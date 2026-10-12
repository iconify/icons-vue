<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e7wxh0bvw"/><path class="byhidvb7y"/><path class="fquka4bot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:real-estate-agent" /></template>
<style>
.byhidvb7y {
  d: path("M2.75 21.25V20a4.5 4.5 0 0 1 4.5-4.5h3.5a4.5 4.5 0 0 1 4.5 4.5v1.25Z");
}

.e7wxh0bvw {
  cx: 9px;
  cy: 7.25px;
  r: 3.75px;
}

.fquka4bot {
  d: path("m9 15.5l-.9 3l.9 1.25l.9-1.25Zm6-5.75V6.5q0-.75.59-1.22l1.95-1.56q.59-.47 1.18 0l1.94 1.56q.59.47.59 1.22v3.25q0 .75-.75.75h-4.75q-.75 0-.75-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
