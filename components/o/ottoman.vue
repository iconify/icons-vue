<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d90huux3l"/><rect class="m0gzhmbbc"/><path class="v1473tbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ottoman" /></template>
<style>
.d90huux3l {
  width: 16.5px;
  height: 4.5px;
  x: 3.75px;
  y: 6.25px;
  rx: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0gzhmbbc {
  width: 13.5px;
  height: 8.5px;
  x: 5.25px;
  y: 10.75px;
  rx: 2px;
}

.v1473tbpo {
  d: path("M7.75 19.25v2m8.5-2v2");
}

</style>
