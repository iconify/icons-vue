<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kamdbib6v"/><path class="pmuiqo95v"/><path class="kt4_ogrrr"/><path class="hgjyjobhk"/><path class="gvpticbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waist-measure-outline-thin" /></template>
<style>
.gvpticbjc {
  d: path("M18 7v4");
}

.hgjyjobhk {
  d: path("M12 7v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kamdbib6v {
  d: path("M2 7h20");
}

.kt4_ogrrr {
  d: path("M6 7v4");
}

.pmuiqo95v {
  d: path("M2 17h20");
}

</style>
