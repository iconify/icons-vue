<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="emvotkb4z"/><path class="nnfdo4bja"/><path class="j2hnp9b4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:percent-outline-bold" /></template>
<style>
.emvotkb4z {
  d: path("M4 20 20 4");
}

.j2hnp9b4t {
  d: path("M15 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nnfdo4bja {
  d: path("M5 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
