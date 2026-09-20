<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v8fbd0blu"/><path class="h0xx2obvc"/><path class="oyo-f5llb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-websocket-outline-thin" /></template>
<style>
.h0xx2obvc {
  d: path("M13 12h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oyo-f5llb {
  d: path("M16 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.v8fbd0blu {
  d: path("M7.5 6H10a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3Z");
}

</style>
