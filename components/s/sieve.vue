<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mv2wmobfw"/><path class="xzt8_p54b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sieve" /></template>
<style>
.mv2wmobfw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 8.75h14a7 7 0 0 1-14 0m.8 3.25h12.4m-6.2-3.25v7m-7-7h-1.5m15.5 0h3");
}

.xzt8_p54b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 19h.01M13 20.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
