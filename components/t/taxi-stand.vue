<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="i5zwh6bhl"/><path class="a4jzribex"/><path class="wc4qhmllt"/><rect class="cews8cbyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taxi-stand" /></template>
<style>
.a4jzribex {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15.75h.01m6.74 0h.01");
}

.cews8cbyi {
  width: 4.5px;
  height: 4.5px;
  x: 16.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.i5zwh6bhl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.11 14.57l1.03-2.64Q4.5 11 5.5 11h7.75q1 0 1.36.93l1.03 2.64q.36.93.36 1.93v1.75q0 1-1 1H3.75q-1 0-1-1V16.5q0-1 .36-1.93");
}

.wc4qhmllt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 19.25v2m9.25-2v2m5-14v14M7.75 8h3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
