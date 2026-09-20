<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n-059ea3n"/><path class="vxqaiwbbu"/><path class="gcu5j9bzw"/><path class="wo23ajbmh"/><path class="rm0jxkbqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:message-split-outline-bold" /></template>
<style>
.gcu5j9bzw {
  d: path("M14 4h3v3");
}

.n-059ea3n {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rm0jxkbqz {
  d: path("M14 20h3v-3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vxqaiwbbu {
  d: path("m9 12 8 -8");
}

.wo23ajbmh {
  d: path("m9 12 8 8");
}

</style>
