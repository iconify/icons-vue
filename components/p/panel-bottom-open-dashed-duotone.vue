<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rar6yubnd"/><path class="c-yqibcyj"/><path class="al3d8cbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-open-dashed-duotone" /></template>
<style>
.al3d8cbli {
  d: path("M9 11L12 8L15 11");
}

.c-yqibcyj {
  d: path("M6 3C4.34315 3 3 4.34315 3 6M21 6C21 4.34315 19.6569 3 18 3M3 10V11M21 10V11M10.5 3H13.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rar6yubnd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 14L21 14C21.5523 14 22 14.4477 22 15L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 15C2 14.4477 2.4477 14 3 14Z");
  stroke: none;
}

</style>
