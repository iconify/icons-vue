<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t9l7d0eki"/><path class="i6lzm3bun"/><path class="ev_frlb7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stop-search-outline-bold" /></template>
<style>
.ev_frlb7a {
  d: path("M16 9h6v6h-6Z");
}

.i6lzm3bun {
  d: path("M5.5 13 3 15.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t9l7d0eki {
  d: path("M4 10a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

</style>
