<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ndtiqfb4f"/><path class="ueyyuelny"/><path class="izxeldb4t"/><path class="fg09jpbsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sugar-duotone-thin" /></template>
<style>
.fg09jpbsd {
  d: path("M13 5h8v8h-8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izxeldb4t {
  d: path("M3 11h8v8H3Z");
}

.ndtiqfb4f {
  fill: currentColor;
  d: path("M3 11h8v8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ueyyuelny {
  fill: currentColor;
  d: path("M13 5h8v8h-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
