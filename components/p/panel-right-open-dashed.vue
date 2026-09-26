<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lkgbbu07j"/><path class="hhirdqpne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-open-dashed" /></template>
<style>
.hhirdqpne {
  d: path("M11 9L8 12L11 15");
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
