<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lf-nsfckx"/><rect class="e0auq8rqk"/><rect class="adczez6dm"/><path class="zh6ue0kmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swimming-goggles" /></template>
<style>
.adczez6dm {
  width: 6.5px;
  height: 5px;
  x: 13.25px;
  y: 6.25px;
  rx: 2.5px;
}

.e0auq8rqk {
  width: 6.5px;
  height: 5px;
  x: 4.25px;
  y: 6.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf-nsfckx {
  d: path("M2.75 8.75h1.5m15.5 0h1.5");
}

.zh6ue0kmc {
  d: path("M10.75 8.75c.83-1 1.67-1 2.5 0m-10.5 9c1.54 0 1.54-1 3.08-1s1.54 1 3.08 1s1.54-1 3.08-1s1.54 1 3.08 1s1.54-1 3.08-1s1.54 1 3.08 1");
}

</style>
