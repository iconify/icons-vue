<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lh2oavbry"/><path class="rxtayfdmd"/><path class="vewuq0b_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-sticker-roll" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lh2oavbry {
  d: path("M2.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.rxtayfdmd {
  d: path("M7 12h14.5v6.5h-13M7 7.5h.01");
}

.vewuq0b_b {
  d: path("M9.75 15.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
