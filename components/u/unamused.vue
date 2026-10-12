<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="cb3bvxiwe"/><path class="gxspifb3m"/><path class="ps9ryfu4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:unamused" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.cb3bvxiwe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 8.75h3.5m2.5 0h3.5");
}

.gxspifb3m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.75h.01m5.99 0h.01");
}

.ps9ryfu4z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 15.75L14.5 15");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
