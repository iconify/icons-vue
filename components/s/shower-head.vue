<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bf3ytemcs"/><path class="j17i2lb0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shower-head" /></template>
<style>
.bf3ytemcs {
  d: path("M3.75 5.25H7l3.5 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j17i2lb0q {
  d: path("m12.33 8.22l4.59 1.81q.93.37.22 1.08l-4.28 4.28q-.71.71-1.08-.22l-1.81-4.59q-.37-.93.34-1.64l.38-.38q.71-.71 1.64-.34m2.52 7.68l1.05 1.05m.9.9l1.05 1.05m-1.6-4.4l1.05 1.05m.9.9l1.05 1.05m-1.6-4.4l1.05 1.05m.9.9l1.05 1.05");
}

</style>
