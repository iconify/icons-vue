<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hhycw79tw"/><path class="v3luf5bwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-send" /></template>
<style>
.hhycw79tw {
  width: 14.5px;
  height: 12px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3luf5bwj {
  d: path("m6 10.75l3.65 2.75c.8.6 1.9.6 2.7 0L16 10.75M15.75 5h4.75m-2-2.25L20.75 5L18.5 7.25");
}

</style>
