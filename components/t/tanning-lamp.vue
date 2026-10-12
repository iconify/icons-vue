<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2qqjibgy"/><rect class="otcf02a2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tanning-lamp" /></template>
<style>
.a2qqjibgy {
  d: path("M8.25 2.75h7.5q1.25 0 1.88 1.08l2.24 3.84q.63 1.08-.62 1.08H4.75q-1.25 0-.62-1.08l2.24-3.84Q7 2.75 8.25 2.75m-1 3h9.5M7 11.5l-1 2.25m6-2.25V14m5-2.5l1 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.otcf02a2e {
  width: 18.5px;
  height: 3.75px;
  x: 2.75px;
  y: 17.5px;
  rx: 1.5px;
}

</style>
