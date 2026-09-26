<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="a8skcubwr"/><path class="ub7gp7b_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-plus-fill" /></template>
<style>
.a8skcubwr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4C3.34315 4 2 5.34315 2 7V17C2 18.6569 3.34315 20 5 20H13V14C13 12.3431 14.3431 11 16 11H22V7C22 5.34315 20.6569 4 19 4H5ZM13.5 8.5C13.5 9.3284 12.8284 10 12 10C11.1716 10 10.5 9.3284 10.5 8.5C10.5 7.6716 11.1716 7 12 7C12.8284 7 13.5 7.6716 13.5 8.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ub7gp7b_j {
  d: path("M22 10V7C22 5.34315 20.6569 4 19 4H5C3.34315 4 2 5.34315 2 7V17C2 18.6569 3.34315 20 5 20H12M19 14V20M22 17H16");
}

</style>
