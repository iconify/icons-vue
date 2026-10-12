<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fial555dm"/><path class="uhsv2cbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tunic" /></template>
<style>
.fial555dm {
  d: path("M9.5 2.75h5q1 0 1.92.39l1.66.72q.92.39 1.41 1.26l1.27 2.26q.49.87-.49 1.07l-1.79.35q-.98.2-.78 1.18l2.1 10.29q.2.98-.8.98H5q-1 0-.8-.98L6.3 9.98Q6.5 9 5.52 8.8l-1.79-.35q-.98-.2-.49-1.07l1.27-2.26Q5 4.25 5.92 3.86l1.66-.72q.92-.39 1.92-.39");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uhsv2cbdc {
  d: path("M10 2.75v1a2 2 0 0 0 4 0v-1m-2 3v2m-5 13.5v-3m10 3v-3M5.8 12.5h12.4");
}

</style>
