<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lps3h3ksm"/><path class="fjjsu0bnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pipette-sharp" /></template>
<style>
.fjjsu0bnk {
  d: path("m12.88 7.23l2.83-2.83a2.75 2.75 0 0 1 3.89 3.89l-2.83 2.83Zm-6.01 9.9l-2.12 2.12");
}

.lps3h3ksm {
  d: path("m13.59 7.93l2.48 2.48l-5.66 5.66l-3.54 1.06l1.06-3.54Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
