<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ya-dvabix"/><path class="vf2cjpyzu"/><path class="ya5oksyke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sticky-note-duotone-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vf2cjpyzu {
  d: path("M3 3h18v12l-6 6H3Z");
}

.ya-dvabix {
  fill: currentColor;
  d: path("M3 3h18v12l-6 6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ya5oksyke {
  d: path("M21 15h-6v6");
}

</style>
