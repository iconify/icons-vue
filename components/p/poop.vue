<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="byrujf6ax"/><path class="b9mcxsbuu"/><path class="g545es9sr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:poop" /></template>
<style>
.b9mcxsbuu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 13.75h.01m4.49 0h.01");
}

.byrujf6ax {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 21.25h11.5a2.75 2.75 0 0 0 .5-5.45a2.5 2.5 0 0 0-1.5-4.8a3.25 3.25 0 0 0-3.5-4.25c.5-1.25 0-2.75-1.5-3.5c.25 1.5-1 2.5-2.5 2.75a3 3 0 0 0-2 5a2.5 2.5 0 0 0-1.5 4.8a2.75 2.75 0 0 0 .5 5.45");
}

.g545es9sr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17.75c1.4.75 3.1.75 4.5 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
