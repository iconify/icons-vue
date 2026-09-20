<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zc40vp7yl"/><path class="c6yqvq36o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:taco-outline-bold" /></template>
<style>
.c6yqvq36o {
  d: path("M5 11c2 -3 4 -1 7 -3s5 1 7 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zc40vp7yl {
  d: path("M4 11c0 5 3 8 8 8s8 -3 8 -8Z");
}

</style>
