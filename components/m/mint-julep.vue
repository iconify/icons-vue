<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xn5npbbjl"/><path class="h7renbb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mint-julep" /></template>
<style>
.h7renbb6k {
  d: path("M14 8.25q.5-5.75 6-5.75q-.5 5.5-6 5.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xn5npbbjl {
  d: path("M6 10h12v9q0 2-2 2H8q-2 0-2-2Zm0 0q6-4 12 0");
}

</style>
