<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xx6l64bvs"/><path class="djqc4ackk"/><path class="yaum7gn-a"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:picnic-duotone-thin" /></template>
<style>
.djqc4ackk {
  d: path("M5 9v9h14V9Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.xx6l64bvs {
  fill: currentColor;
  d: path("M5 9v9h14V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yaum7gn-a {
  d: path("M7 9a5 5 0 0 1 10 0");
}

</style>
