<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yzge-q6go"/><path class="s-378bj6v"/><rect class="tk8z1_bfm"/><rect class="l4d2waclf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-telescope" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4d2waclf {
  width: 5px;
  height: 4.25px;
  x: 8.5px;
  y: 17px;
  rx: 0.75px;
}

.s-378bj6v {
  d: path("m18.56 9.36l1.38-1.72q.31-.39.71-.09l.2.15q.4.3.09.69l-1.38 1.72q-.31.39-.71.09l-.2-.15q-.4-.3-.09-.69M11 7v2.5m0 5V17");
}

.tk8z1_bfm {
  width: 5px;
  height: 4.25px;
  x: 8.5px;
  y: 2.75px;
  rx: 0.75px;
}

.yzge-q6go {
  width: 14px;
  height: 5px;
  x: 3.5px;
  y: 9.5px;
  rx: 1.5px;
}

</style>
