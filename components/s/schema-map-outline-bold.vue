<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="baerff2wm"/><path class="pmhsn037r"/><path class="arq593bkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:schema-map-outline-bold" /></template>
<style>
.arq593bkp {
  d: path("m9 9 6 6");
}

.baerff2wm {
  d: path("M2 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.pmhsn037r {
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
