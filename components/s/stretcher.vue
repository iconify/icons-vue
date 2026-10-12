<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="epmaifbxu"/><circle class="b1g9m1bqw"/><circle class="otw2wcc-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stretcher" /></template>
<style>
.b1g9m1bqw {
  cx: 7px;
  cy: 19.5px;
  r: 1.5px;
}

.epmaifbxu {
  d: path("M6 8h12M2.75 11h18.5M7 11v7m10-7v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.otw2wcc-c {
  cx: 17px;
  cy: 19.5px;
  r: 1.5px;
}

</style>
