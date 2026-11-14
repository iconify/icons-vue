<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkwzcqb9a"/><path class="m3johub1v"/><path class="csx24vbrd"/><path class="dd95arbbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reuse-centre" /></template>
<style>
.bkwzcqb9a {
  d: path("M3 21V9l9-6l9 6v12Z");
}

.csx24vbrd {
  d: path("M14 12.625za.84.84 0 0 0 1.125-.375a.347.347 0 0 0-.42-.485l-.66.22a.347.347 0 0 0-.045.64M14.75 15a3 3 0 0 1-5.5 0");
}

.dd95arbbd {
  d: path("M10 15.375za.84.84 0 0 0-1.125.375a.347.347 0 0 0 .42.485l.66-.22a.347.347 0 0 0 .045-.64");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m3johub1v {
  d: path("M9.25 13a3 3 0 0 1 5.5 0");
}

</style>
