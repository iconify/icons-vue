<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q8-0ejn0y"/><path class="f69zonn4h"/><path class="xeo8ox-td"/><path class="ey7vq22fn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:report-user-outline-regular" /></template>
<style>
.ey7vq22fn {
  d: path("m16 5 5 5h-5");
}

.f69zonn4h {
  d: path("M4 17a4 4 0 0 1 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q8-0ejn0y {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xeo8ox-td {
  d: path("M16 5v15");
}

</style>
