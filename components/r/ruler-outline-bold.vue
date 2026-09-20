<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qvq8nib-l"/><path class="p4maaes8e"/><path class="gte-olbep"/><path class="jz3tcofhe"/><path class="ktxx-etqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ruler-outline-bold" /></template>
<style>
.gte-olbep {
  d: path("M10 8v3.5");
}

.jz3tcofhe {
  d: path("M14 8v3.5");
}

.ktxx-etqf {
  d: path("M18 8v3.5");
}

.p4maaes8e {
  d: path("M6 8v3.5");
}

.qvq8nib-l {
  d: path("M2 12a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
