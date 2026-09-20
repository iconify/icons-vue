<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l2wdis8zs"/><path class="o77mms0ex"/><path class="vr9ht74fa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pharmacy-duotone-bold" /></template>
<style>
.l2wdis8zs {
  fill: currentColor;
  d: path("M3 11h18a9 9 0 0 1 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o77mms0ex {
  d: path("M3 11h18a9 9 0 0 1 -18 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vr9ht74fa {
  d: path("m8 3 7 7");
}

</style>
