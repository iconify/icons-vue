<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="s3emwbbip"/><path class="kot_bbcsf"/><path class="j0f5vuboa"/><path class="cx-q8ul9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mood-tracker" /></template>
<style>
.cx-q8ul9v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 15.5c.85 1.1 1.95 1.75 3.25 1.75s2.4-.65 3.25-1.75");
}

.j0f5vuboa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01m4.99 0h.01");
}

.kot_bbcsf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75v4.5m8-4.5v4.5");
}

.s3emwbbip {
  width: 16.5px;
  height: 16px;
  x: 3.75px;
  y: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
