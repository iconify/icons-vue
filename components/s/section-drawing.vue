<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hoi44xq4a"/><path class="f1_cau6cr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:section-drawing" /></template>
<style>
.f1_cau6cr {
  d: path("M6 16.5h12M7.5 19l2-2.5M11 19l2-2.5m1.5 2.5l2-2.5m-8 0v-9h7v9m-7-4.5h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hoi44xq4a {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
