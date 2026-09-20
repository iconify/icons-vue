<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m3tfe9bwc"/><path class="mjze8rg7o"/><path class="ae0h5kb0o"/><path class="x3sflacnk"/><path class="wtnr1t2-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:post-filter-duotone-bold" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.m3tfe9bwc {
  fill: currentColor;
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mjze8rg7o {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wtnr1t2-w {
  d: path("M9 21h6");
}

.x3sflacnk {
  d: path("M9 18h6");
}

</style>
