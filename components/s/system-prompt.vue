<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mwhs48gfm"/><path class="fpn4ubbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:system-prompt" /></template>
<style>
.fpn4ubbrd {
  d: path("m6.25 7l2 1.75l-2 1.75m4 0h2M19 15l-2.75 3.5h2.5L18 21.25l3-3.5h-2.5z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwhs48gfm {
  width: 14.5px;
  height: 10px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>
