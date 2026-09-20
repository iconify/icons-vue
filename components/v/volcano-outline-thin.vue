<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l4f5m0byt"/><path class="a8u3jfbrq"/><path class="cvahx_bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volcano-outline-thin" /></template>
<style>
.a8u3jfbrq {
  d: path("M10 13V9h4v4");
}

.cvahx_bgf {
  d: path("m9 9 3 -3 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4f5m0byt {
  d: path("m3 20 7 -7h4l7 7Z");
}

</style>
