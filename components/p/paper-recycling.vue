<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ihvx1r3bc"/><rect class="rjlj4mu8q"/><path class="b6n6u0v1b"/><path class="v4aqohbrc"/><path class="a-h60nb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-recycling" /></template>
<style>
.a-h60nb3w {
  d: path("M14 12v1.5h-1.5");
}

.b6n6u0v1b {
  d: path("M4.25 9.75h15.5l-1 10a1.5 1.5 0 0 1-1.5 1.5H6.75a1.5 1.5 0 0 1-1.5-1.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihvx1r3bc {
  d: path("M8.75 6.25v-2.5a1 1 0 0 1 1-1h4.5a1 1 0 0 1 1 1v2.5Z");
}

.rjlj4mu8q {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 6.25px;
  rx: 1.5px;
}

.v4aqohbrc {
  d: path("M14.75 15.5a2.75 2.75 0 1 1-.75-2");
}

</style>
