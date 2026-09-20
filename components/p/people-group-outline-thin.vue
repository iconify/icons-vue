<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="keqc2pbxm"/><path class="ph-bhccoq"/><path class="igam7_b3d"/><path class="hlqoyz1hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:people-group-outline-thin" /></template>
<style>
.hlqoyz1hh {
  d: path("M3 20a9 9 0 0 1 18 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.igam7_b3d {
  d: path("M16 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.keqc2pbxm {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ph-bhccoq {
  d: path("M10 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
