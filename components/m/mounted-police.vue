<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m2myy79hx"/><path class="utdabybdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mounted-police" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2myy79hx {
  d: path("M3 21.5V12a9 9 0 0 1 18 0v9.5h-3.5V12a5.5 5.5 0 0 0-11 0v9.5Z");
}

.utdabybdb {
  d: path("m12.5 12.75l.123.307a1.5 1.5 0 0 0 1.393.943h.234a.47.47 0 0 1 .309.823l-.333.291a1.5 1.5 0 0 0-.449 1.56l.098.326a.47.47 0 0 1-.711.526l-.332-.221a1.5 1.5 0 0 0-1.664 0l-.332.221a.47.47 0 0 1-.711-.526l.098-.326a1.5 1.5 0 0 0-.449-1.56l-.333-.291A.47.47 0 0 1 9.75 14h.234a1.5 1.5 0 0 0 1.393-.943l.123-.307a.539.539 0 0 1 1 0");
}

</style>
