<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="sfrtbsbjm"/><path class="wybyc7b4n"/><path class="xzw-2u4_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pigeon" /></template>
<style>
.sfrtbsbjm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7c0-1.25 1-2.5 2.25-2.5S10 5.75 10 7c0 .6-.15 1.1-.4 1.5c3.65.75 7.15 2.75 9.15 4.5L21 14.25c.35.2.25.75-.15.75H18c-1.25 2-3.5 3.25-6 3.25c-4 0-7.75-2-7.75-5.5c0-1.5 1-2.75 2.25-3.5c-.6-.55-1-1.35-1-2.25");
}

.wybyc7b4n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 10.25c1.75 1 3.75 1.1 5.5.1m.25 2.15q2.625 1.875 6 2.25M5.6 6.9l-1.85.7m6.75 10.55L9 20.75m4.5-2.65l.5 2.65");
}

.xzw-2u4_v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.6 6.6h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
