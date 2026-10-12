<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="ovi-hdc4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recycling-point" /></template>
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

.ovi-hdc4u {
  d: path("m13.08 7.93l3.24 5.81m-2.09-.67l2.09.67l.53-2.13m-1.01 5.14H9.36m1.6-1.5l-1.6 1.5l1.6 1.5m-3.88-3.44l3.24-5.8m.53 2.13l-.53-2.13l-2.09.67");
}

</style>
