<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sjmvcxbpe"/><path class="l0v-b4kbr"/><path class="ug4kkubvk"/><path class="ipv0cebdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transform-outline-bold" /></template>
<style>
.ipv0cebdm {
  d: path("M13 16a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sjmvcxbpe {
  d: path("M2 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ug4kkubvk {
  d: path("m13 9 3 3 -3 3");
}

</style>
