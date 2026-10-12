<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cwfg1k7fy"/><path class="xhb0yy15h"/><path class="rq8879bxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rhino" /></template>
<style>
.cwfg1k7fy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.75c1 0 1.75-.5 2.25-1.25L7.75 9l.5-2L9.5 8.5H15c3.5 0 6.25 2.25 6.25 5.75v1.25c0 .75-.5 1.25-1.25 1.25l-.5 3.5h-2l-.5-3.5h-5.5l-.5 3.5H9l-.5-3.75c-2 0-3.75-.75-5-1.75l-.5-.5c-.5-.5-.25-1.5.5-1.5Z");
}

.rq8879bxe {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 11h.01");
}

.xhb0yy15h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 12.5l-1-4.25c-.1-.6.5-.9.85-.45l1.9 3.7Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
