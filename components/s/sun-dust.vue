<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="btra52bxc"/><path class="j--z5ubop"/><path class="gttf8eb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sun-dust" /></template>
<style>
.btra52bxc {
  cx: 12px;
  cy: 9.5px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gttf8eb9g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 13.75h.01M9.5 21h.01M17 21h.01");
}

.j--z5ubop {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5h-1m2.61-3.89L7.4 4.9M12 4V3m3.89 2.61l.71-.71m.9 4.6h1M3.75 17.25q2.06-1.5 4.13 0t4.12 0t4.13 0t4.12 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
