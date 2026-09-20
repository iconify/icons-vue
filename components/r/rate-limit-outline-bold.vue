<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="h5uycs4sy"/><path class="wp75hkmty"/><path class="y2lgilb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rate-limit-outline-bold" /></template>
<style>
.h5uycs4sy {
  d: path("M2 16h8");
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.o0-3vqblf {
  d: path("M2 8h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wp75hkmty {
  d: path("M11 7v10");
}

.y2lgilb0y {
  d: path("M13 12h9");
}

</style>
