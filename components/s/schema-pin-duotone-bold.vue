<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="whb7_bbil"/><path class="dpra8nb8c"/><path class="hk-jkdb0v"/><path class="ah8uvpf1o"/><path class="e6q34etyy"/><path class="g22ksobnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:schema-pin-duotone-bold" /></template>
<style>
.ah8uvpf1o {
  d: path("M3 10h13");
}

.dpra8nb8c {
  fill: currentColor;
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e6q34etyy {
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.g22ksobnl {
  d: path("M19 14v4");
}

.hk-jkdb0v {
  d: path("M3 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.whb7_bbil {
  fill: currentColor;
  d: path("M3 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
