<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w1ghlpbud"/><path class="b_zhkbf3c"/><rect class="u74et4b5e"/><path class="ll3_6zypj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:photo-corners" /></template>
<style>
.b_zhkbf3c {
  d: path("M7.25 2.75v18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ll3_6zypj {
  d: path("M10.25 17h6.5");
}

.u74et4b5e {
  width: 6.5px;
  height: 6px;
  x: 10.25px;
  y: 7.25px;
  rx: 1px;
}

.w1ghlpbud {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
