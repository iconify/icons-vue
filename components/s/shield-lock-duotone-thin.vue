<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crzn5obfu"/><path class="knwvyb4jt"/><path class="ymp2b4b6u"/><path class="mkd2anbbl"/><path class="ijgmec7ta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shield-lock-duotone-thin" /></template>
<style>
.crzn5obfu {
  fill: currentColor;
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijgmec7ta {
  d: path("M10 11a2 2 0 0 1 4 0");
}

.knwvyb4jt {
  fill: currentColor;
  d: path("M9 11h6v5H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mkd2anbbl {
  d: path("M9 11h6v5H9Z");
}

.ymp2b4b6u {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
