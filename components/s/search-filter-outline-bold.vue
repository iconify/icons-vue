<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r441scx-k"/><path class="mktkir7xv"/><path class="wlknapbcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:search-filter-outline-bold" /></template>
<style>
.mktkir7xv {
  d: path("m5 13 -2 2");
}

.r441scx-k {
  d: path("M4 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wlknapbcp {
  d: path("M15 8h7l-2 2v8h-3v-8Z");
}

</style>
