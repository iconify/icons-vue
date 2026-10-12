<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ztizm7lpg"/><path class="bil9-rkpq"/><path class="kijy6ccde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:server-log" /></template>
<style>
.bil9-rkpq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 7h.01m2.99 0h.01");
}

.kijy6ccde {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.5h16.5m-16.5 3.25h12.5M3.75 21h8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ztizm7lpg {
  width: 18.5px;
  height: 7.5px;
  x: 2.75px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

</style>
