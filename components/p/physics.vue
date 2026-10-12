<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rodzibcla"/><circle class="z2w-83bda"/><path class="z5-oagmmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:physics" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rodzibcla {
  d: path("M6.75 3.75h10.5m-5.25 0l2.13 8.36");
}

.z2w-83bda {
  cx: 15px;
  cy: 15.5px;
  r: 2.5px;
}

.z5-oagmmd {
  d: path("M6.1 19.96a17.25 17.25 0 0 0 11.8 0");
}

</style>
