<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmaccdclu"/><path class="t2e2ofbwt"/><path class="f8gsx7b5s"/><path class="gcalxb98a"/><path class="qtxvlht3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:milk-duotone-thin" /></template>
<style>
.f8gsx7b5s {
  d: path("M6 8h12");
}

.gcalxb98a {
  d: path("M8 13h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmaccdclu {
  fill: currentColor;
  d: path("M6 21V8l4 -4h4l4 4v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.t2e2ofbwt {
  d: path("M6 21V8l4 -4h4l4 4v13Z");
}

</style>
