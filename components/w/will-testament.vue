<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="j3k6s3bra"/><path class="h9mvzmb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:will-testament" /></template>
<style>
.h9mvzmb0w {
  d: path("M6 7h4.5M6 10.25h3m7.75 2.5h4q.5 0 .36.48l-.97 3.29q-.14.48 0 .96l.97 3.29q.14.48-.36.48h-4q-.5 0-.36-.48l.97-3.29q.14-.48 0-.96l-.97-3.29q-.14-.48.36-.48");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3k6s3bra {
  width: 10.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
