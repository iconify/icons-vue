<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e3a4jwzia"/><path class="kn-efdc_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:theater-mode" /></template>
<style>
.e3a4jwzia {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kn-efdc_v {
  d: path("M7.5 12h9m-7-2l-2 2l2 2m5-4l2 2l-2 2");
}

</style>
