<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hs57snbui"/><rect class="ck7j53nfp"/><rect class="or5h1rb1n"/><path class="huw42i8ag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timeline-edit" /></template>
<style>
.ck7j53nfp {
  width: 4.75px;
  height: 4px;
  x: 14.5px;
  y: 8px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs57snbui {
  width: 6.75px;
  height: 4px;
  x: 2.75px;
  y: 8px;
  rx: 1px;
}

.huw42i8ag {
  d: path("M10.5 2.75h3q.75 0 .75.75V4q0 .75-.56 1.25l-1.13 1q-.56.5-1.12 0l-1.13-1q-.56-.5-.56-1.25v-.5q0-.75.75-.75m1.5 4v14.5");
}

.or5h1rb1n {
  width: 6.75px;
  height: 4px;
  x: 14.5px;
  y: 15px;
  rx: 1px;
}

</style>
