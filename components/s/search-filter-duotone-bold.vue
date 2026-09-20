<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="waz5v9y7f"/><path class="k75umlios"/><path class="r441scx-k"/><path class="mktkir7xv"/><path class="wlknapbcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:search-filter-duotone-bold" /></template>
<style>
.k75umlios {
  fill: currentColor;
  d: path("M15 8h7l-2 2v8h-3v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

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

.waz5v9y7f {
  fill: currentColor;
  d: path("M4 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wlknapbcp {
  d: path("M15 8h7l-2 2v8h-3v-8Z");
}

</style>
