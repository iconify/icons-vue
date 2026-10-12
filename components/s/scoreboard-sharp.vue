<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h7hbgfboc"/><path class="ogmru5v8n"/><path class="o0w7y1jzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scoreboard-sharp" /></template>
<style>
.h7hbgfboc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v14H2.75zm4.75 14v3.5m9-3.5v3.5");
}

.o0w7y1jzr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.25h.01m-.01 3.5h.01");
}

.ogmru5v8n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9.25a1.75 1.75 0 0 1 3.5 0c0 1.5-3.5 3-3.5 5h3.5m6-5.5L17 7.5v6.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
