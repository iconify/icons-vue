<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cy3ajujxf"/><circle class="nr25s3eql"/><path class="i7yv4ebjb"/><path class="xqx6wkbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:piggy-bank-minus" /></template>
<style>
.cy3ajujxf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14A7.5 5.75 0 0 1 11 8.25h2a7 5.75 0 0 1 5.75 3h.5a1.5 1.5 0 0 1 1.5 1.5V15a1.5 1.5 0 0 1-1.5 1.5h-.9a7 5.75 0 0 1-2.6 2.25v1a1 1 0 0 1-1 1H13a1 1 0 0 1-1-1v-.5H9.25v.5a1 1 0 0 1-1 1H6.5a1 1 0 0 1-1-1v-1.8a5.75 5.75 0 0 1-2-3.95");
}

.i7yv4ebjb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 11.25h3");
}

.nr25s3eql {
  cx: 11.5px;
  cy: 4.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xqx6wkbem {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 13h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
