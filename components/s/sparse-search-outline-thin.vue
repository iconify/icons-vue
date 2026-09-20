<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7nacdcee"/><path class="p2x4fkb_u"/><path class="pt-3kkb2k"/><path class="vd0jm7r_j"/><path class="p0o5ir5ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sparse-search-outline-thin" /></template>
<style>
.b7nacdcee {
  d: path("M3 6h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p0o5ir5ue {
  d: path("M15 16h6");
}

.p2x4fkb_u {
  d: path("M15 6h6");
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.vd0jm7r_j {
  d: path("M3 16h6");
}

</style>
