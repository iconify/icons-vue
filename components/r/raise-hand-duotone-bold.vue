<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uvrlgpb3k"/><path class="e5m-dqb4m"/><path class="n5c3em2az"/><path class="xar3kncqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:raise-hand-duotone-bold" /></template>
<style>
.e5m-dqb4m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 9V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n5c3em2az {
  d: path("M7 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v4a2 2 0 0 1 4 0v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uvrlgpb3k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v4a2 2 0 0 1 4 0v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xar3kncqc {
  d: path("M15 9V4");
}

</style>
