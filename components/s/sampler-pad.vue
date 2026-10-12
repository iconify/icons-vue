<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="rqjlqxbxo"/><rect class="xrs144bol"/><rect class="q12y57b_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sampler-pad" /></template>
<style>
.a_-q_pb0z {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q12y57b_j {
  width: 4.5px;
  height: 4.5px;
  x: 13.75px;
  y: 13.5px;
  rx: 1px;
}

.rqjlqxbxo {
  d: path("M6.25 8.25H8l1.5-2.5l2 5l2-5l1.5 2.5h2.75");
}

.xrs144bol {
  width: 4.5px;
  height: 4.5px;
  x: 5.75px;
  y: 13.5px;
  rx: 1px;
}

</style>
