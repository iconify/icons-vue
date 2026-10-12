<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oqhtb4bvj"/><path class="qyz3ynbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rafter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqhtb4bvj {
  width: 2.5px;
  height: 4px;
  x: 10.75px;
  y: 3.5px;
  rx: 0.6px;
}

.qyz3ynbty {
  d: path("M10.75 4.1v2.8q0 .6-.37 1.07l-7.26 9.06q-.37.47-.37-.13v-2.8q0-.6.37-1.07l7.26-9.06q.37-.47.37.13m2.87-.13l7.26 9.06q.37.47.37 1.07v2.8q0 .6-.37.13l-7.26-9.06q-.37-.47-.37-1.07V4.1q0-.6.37-.13M5.25 14.5h13.5m-12.25 0V18m11-3.5V18M6.75 9.75h10.5");
}

</style>
