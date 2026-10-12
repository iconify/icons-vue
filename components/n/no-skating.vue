<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="ad97ixk6g"/><path class="fzu4a77bs"/><path class="kvo-pacvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-skating" /></template>
<style>
.ad97ixk6g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11.5c.5 1 1 1.25 2 1.25h8c1 0 1.5-.25 2-1.25");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fzu4a77bs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15h.01M15 15h.01");
}

.kvo-pacvp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 5.5l13 13");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
