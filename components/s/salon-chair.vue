<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ds5lkub1d"/><rect class="xqq-75bco"/><rect class="ry1lcbb9v"/><path class="xhy92_bjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salon-chair" /></template>
<style>
.ds5lkub1d {
  d: path("M11.25 6.75a5 4 0 0 1 10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ry1lcbb9v {
  width: 12.5px;
  height: 3px;
  x: 5.75px;
  y: 11.75px;
  rx: 1.5px;
}

.xhy92_bjw {
  d: path("M7 11V9.25h5.5m-.5 5.5v4.5m-5 1h10");
}

.xqq-75bco {
  width: 4.5px;
  height: 5.5px;
  x: 13.75px;
  y: 6.25px;
  rx: 2px;
}

</style>
