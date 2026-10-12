<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zyt56mbrm"/><rect class="wsqafx_hw"/><path class="mdv2kmbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:picture-frame" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mdv2kmbso {
  d: path("m6.25 16.25l3.75-4l3 3l1.75-1.75l3 2.75");
}

.wsqafx_hw {
  width: 11.5px;
  height: 9.5px;
  x: 6.25px;
  y: 7.25px;
  rx: 1px;
}

.zyt56mbrm {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

</style>
