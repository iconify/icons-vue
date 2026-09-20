<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j0fn7xluk"/><path class="vks53cb_y"/><path class="j1y852r1k"/><path class="jbwvw6voa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:similarity-duotone-bold" /></template>
<style>
.j0fn7xluk {
  fill: currentColor;
  d: path("m9 5 5 5 -5 5 -5 -5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j1y852r1k {
  d: path("m9 5 5 5 -5 5 -5 -5Z");
}

.jbwvw6voa {
  d: path("m15 9 5 5 -5 5 -5 -5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vks53cb_y {
  fill: currentColor;
  d: path("m15 9 5 5 -5 5 -5 -5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
