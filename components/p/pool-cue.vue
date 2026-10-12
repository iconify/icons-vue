<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pu658ab7h"/><circle class="ybufkabpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pool-cue" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pu658ab7h {
  d: path("m3.64 18.36l5.47-5.47q.64-.64 1.28 0l.72.72q.64.64 0 1.28l-5.47 5.47q-.64.64-1.28 0l-.72-.72q-.64-.64 0-1.28m7.11-5.11l4.5-4.5");
}

.ybufkabpo {
  cx: 18.5px;
  cy: 5.5px;
  r: 2.5px;
}

</style>
