<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nr_te6bbn"/><path class="d2ei2dbum"/><rect class="a2kcwubtg"/><path class="yqj9fng3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vote" /></template>
<style>
.a2kcwubtg {
  width: 16.5px;
  height: 8px;
  x: 3.75px;
  y: 13.25px;
  rx: 2px;
}

.d2ei2dbum {
  d: path("M10.25 6.75L11.5 8l2.25-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr_te6bbn {
  width: 7.5px;
  height: 8px;
  x: 8.25px;
  y: 2.75px;
  rx: 1.25px;
}

.yqj9fng3h {
  d: path("M8.25 16.75h7.5");
}

</style>
