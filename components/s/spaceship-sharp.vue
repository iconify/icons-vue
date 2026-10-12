<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gui52absv"/><circle class="qu-laubmi"/><path class="djjocn4tj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spaceship-sharp" /></template>
<style>
.djjocn4tj {
  d: path("m6.34 10.6l-2.93 1.55l-.66.35l.66.35l2.93 1.55l.66.35v-4.5z");
}

.gui52absv {
  d: path("M8.5 8.5h5c4 0 6.75 1.75 7.75 4c-1 2.25-3.75 4-7.75 4H7v-8zm-.84-.67L6.09 4.67L5.75 4h3l.48.58l2.79 3.34l.48.58H8zm0 9.34l-1.57 3.16l-.34.67h3l.48-.58l2.79-3.34l.48-.58H8z");
}

.qu-laubmi {
  cx: 15.5px;
  cy: 12.5px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
