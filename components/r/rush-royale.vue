<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGRWtPkHEV" class="td6l25wvz"/></defs><path class="nan_ambij"/><use href="#SVGRWtPkHEV" class="c-zrgpb5l"/><use href="#SVGRWtPkHEV" class="c-zrgpb5l"/><path class="ift7a9j0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rush-royale" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ift7a9j0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.635 26.743c.914.59 1.672 1.965 1.672 1.965");
}

.nan_ambij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.478c3.13 0 7.14.13 15.746.556c2.885-5.525 4.548-18.142 3.374-18.582s-3.863-.635-9.731 5.037c-1.223-6.406-6.26-14.523-9.39-14.523s-8.166 8.117-9.388 14.523c-5.868-5.672-8.558-5.477-9.731-5.037s.489 13.057 3.374 18.582c8.605-.426 12.616-.556 15.746-.556");
}

.td6l25wvz {
  fill: none;
  stroke: currentColor;
  d: path("M24 22.967c3.24 2.09 5.93 6.968 5.93 6.968L24 35.216l-5.93-5.28s2.69-4.879 5.93-6.969");
}

</style>
