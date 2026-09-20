<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v2w1pjbld"/><path class="naqjrf_pr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quantization-duotone-bold" /></template>
<style>
.naqjrf_pr {
  d: path("M4 18h4v-4h4v-4h4V6h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v2w1pjbld {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h4v-4h4v-4h4V6h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
