<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oc76koo5n"/><rect class="ymq1ijbor"/><path class="thaya-_nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-cone-site" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oc76koo5n {
  d: path("M11.25 9h1.5q.75 0 .98.71l3.29 10.33q.23.71-.52.71h-9q-.75 0-.52-.71l3.29-10.33q.23-.71.98-.71m-7.5 11.75h16.5m-11.6-6h6.7");
}

.thaya-_nd {
  d: path("M7.75 5.75L6.25 4.5m10 1.25l1.5-1.25");
}

.ymq1ijbor {
  width: 4px;
  height: 3.5px;
  x: 10px;
  y: 5.5px;
  rx: 1.25px;
}

</style>
