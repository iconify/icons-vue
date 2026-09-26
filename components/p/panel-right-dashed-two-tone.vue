<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k-gaiybts"/><path class="lkgbbu07j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-dashed-two-tone" /></template>
<style>
.k-gaiybts {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2H18C20.20914 2 22 3.79086 22 6V18C22 20.20914 20.20914 22 18 22H6C3.79086 22 2 20.20914 2 18V6C2 3.79086 3.79086 2 6 2ZM15 3V21H18C19.65685 21 21 19.65685 21 18V6C21 4.34315 19.65685 3 18 3Z");
  stroke: none;
}

.lkgbbu07j {
  d: path("M15 3H18C19.6569 3 21 4.34315 21 6V18C21 19.6569 19.6569 21 18 21H15V3ZM6 3C4.34315 3 3 4.34315 3 6M3 18C3 19.6569 4.34315 21 6 21M10 3H11M10 21H11M3 10.5V13.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
