<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cx4pz1b4o"/><path class="yx2y4tasg"/><path class="y62iljmfo"/><path class="l9z5uubso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nappy-duotone-thin" /></template>
<style>
.cx4pz1b4o {
  fill: currentColor;
  d: path("M5 8h14l-7 7Z");
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

.l9z5uubso {
  d: path("M15 8V5h4v3");
}

.y62iljmfo {
  d: path("M5 8V5h4v3");
}

.yx2y4tasg {
  d: path("M5 8h14l-7 7Z");
}

</style>
