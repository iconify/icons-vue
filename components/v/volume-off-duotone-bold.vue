<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jhn2mxbpk"/><path class="jmjqszbgk"/><path class="ljir_j9fp"/><path class="ggag34r5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volume-off-duotone-bold" /></template>
<style>
.ggag34r5e {
  d: path("m21 9 -5 5");
}

.jhn2mxbpk {
  fill: currentColor;
  d: path("M8 9H3v6h5l5 5V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jmjqszbgk {
  d: path("M8 9H3v6h5l5 5V4Z");
}

.ljir_j9fp {
  d: path("m16 9 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
