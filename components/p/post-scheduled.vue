<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xdz9fbb1r"/><path class="i51ih_n-e"/><circle class="d4da7x21x"/><path class="mljaf99ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:post-scheduled" /></template>
<style>
.d4da7x21x {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i51ih_n-e {
  d: path("M6.5 7.25h7m-7 3.5h4");
}

.mljaf99ue {
  d: path("M16.75 14.75v2L18 18");
}

.xdz9fbb1r {
  width: 14.5px;
  height: 14.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

</style>
