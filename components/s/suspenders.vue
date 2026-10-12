<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-udisbis"/><rect class="s3cde52cn"/><rect class="gnpyp3bno"/><path class="gkiwkxb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:suspenders" /></template>
<style>
.gkiwkxb2b {
  d: path("M4 21.25V18.5h16v2.75");
}

.gnpyp3bno {
  width: 3px;
  height: 3.5px;
  x: 14px;
  y: 15px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s3cde52cn {
  width: 3px;
  height: 3.5px;
  x: 7px;
  y: 15px;
  rx: 0.75px;
}

.x-udisbis {
  d: path("M8.5 2.75V15m7-12.25V15");
}

</style>
