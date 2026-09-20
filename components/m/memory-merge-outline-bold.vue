<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n0n63pb2v"/><path class="av_43ob7n"/><path class="po8gn9rls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-merge-outline-bold" /></template>
<style>
.av_43ob7n {
  d: path("M7 6h3l3 3h3");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.po8gn9rls {
  d: path("M7 12h3l3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
