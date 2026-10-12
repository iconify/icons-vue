<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x-3ii1okf"/><path class="v29mn7bho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v29mn7bho {
  d: path("M6.75 8.75h2q1.5 0 1.76 1.48l.48 2.79q.26 1.48 1.76 1.48H17q1.5 0 1.7 1.49l.1.77q.2 1.49-1.3 1.49H8q-1.5 0-1.7-1.49l-.85-6.52q-.2-1.49 1.3-1.49m1.75 9.5v3m8-3v3");
}

.x-3ii1okf {
  width: 5px;
  height: 3.5px;
  x: 5.5px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
