<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_ex61jhy"/><circle class="ytopibb5c"/><path class="cqewpwbdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-capsule" /></template>
<style>
.c_ex61jhy {
  d: path("M10.75 3.25h2.5q1.25 0 1.7 1.17l3.85 9.91q.45 1.17-.8 1.17H6q-1.25 0-.8-1.17l3.85-9.91q.45-1.17 1.7-1.17");
}

.cqewpwbdo {
  d: path("M4.25 18h15.5c-1.25 2-4.25 3.25-7.75 3.25S5.5 20 4.25 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ytopibb5c {
  cx: 12px;
  cy: 10px;
  r: 2px;
}

</style>
