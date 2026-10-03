<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jy_6v7b5h"/><path class="q-j_wtmfu"/><path class="o38d90bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:save-check-duotone" /></template>
<style>
.jy_6v7b5h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.7909 3.7909 2 6 2L16.1716 2C16.9672 2 17.7303 2.3161 18.2929 2.8787L21.1213 5.7071C21.6839 6.2697 22 7.0328 22 7.8284L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o38d90bvg {
  d: path("M9 14L11 16L15 12");
}

.q-j_wtmfu {
  fill: currentColor;
  d: path("M7 5C7 4.4477 7.4477 4 8 4L12 4C12.5523 4 13 4.4477 13 5L13 6C13 6.5523 12.5523 7 12 7L8 7C7.4477 7 7 6.5523 7 6L7 5Z");
  stroke: none;
}

</style>
