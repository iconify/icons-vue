<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b73i7f1-c"/><circle class="raw51vchv"/><circle class="pk8yrhbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:truck-loading-ramp-sharp" /></template>
<style>
.b73i7f1-c {
  d: path("M8.25 6V4.75h8.5v4.5h2.905l.445.67l.9 1.35l.25.377V15h-13Zm8.5 3.25V15m-8.5.5V21h-5.5l.34-.37l4.82-5.26l.34-.37z");
}

.pk8yrhbxx {
  cx: 18.5px;
  cy: 19.5px;
  r: 1.5px;
}

.raw51vchv {
  cx: 12.75px;
  cy: 19.5px;
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
