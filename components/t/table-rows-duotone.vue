<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dl2nz2boo"/><path class="jfp2fyuan"/><path class="onntuwhvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-duotone" /></template>
<style>
.dl2nz2boo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2H18C20.20914 2 22 3.79086 22 6V18C22 20.20914 20.20914 22 18 22H6C3.79086 22 2 20.20914 2 18V6C2 3.79086 3.79086 2 6 2Z");
  stroke: none;
}

.jfp2fyuan {
  fill: currentColor;
  d: path("M6 3H9V21H6C4.34315 21 3 19.65685 3 18V6C3 4.34315 4.34315 3 6 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.onntuwhvq {
  d: path("M6 3H18C19.65685 3 21 4.34315 21 6V18C21 19.65685 19.65685 21 18 21H6C4.34315 21 3 19.65685 3 18V6C3 4.34315 4.34315 3 6 3ZM9 3V21M9 12H21");
}

</style>
