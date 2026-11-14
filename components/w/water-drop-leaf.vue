<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bhqwb6ryv"/><path class="ay767rrlm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-drop-leaf" /></template>
<style>
.ay767rrlm {
  d: path("M13.454 16.021a3 3 0 0 1-2.433 2.433");
}

.bhqwb6ryv {
  d: path("m10.5 5.5l4.75 6.25a6 6 0 1 1-9.5 0Zm3.5 0q-.25-3.75 7-3q.25 3.75-7 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
