<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wt0ty69zl"/><circle class="drtvz1btn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:palms-up-sharp" /></template>
<style>
.drtvz1btn {
  cx: 12px;
  cy: 8.5px;
  r: 2.25px;
}

.wt0ty69zl {
  d: path("M10.5 18.75q-7.75 0-7.75-9.25a1.5 1.5 0 0 1 3 0q0 6.25 4.75 6.25Zm3 0q7.75 0 7.75-9.25a1.5 1.5 0 0 0-3 0q0 6.25-4.75 6.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
