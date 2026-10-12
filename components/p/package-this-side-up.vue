<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ru6wkbb1e"/><path class="cdixnqw_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:package-this-side-up" /></template>
<style>
.cdixnqw_i {
  d: path("M8.75 16.5V8m-2 2l2-2l2 2m4.5 6.5V8m-2 2l2-2l2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ru6wkbb1e {
  width: 18.5px;
  height: 17.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 1.5px;
}

</style>
