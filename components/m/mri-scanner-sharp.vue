<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ha2z4qbtg"/><circle class="c2vbuccni"/><path class="hdj66lbws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mri-scanner-sharp" /></template>
<style>
.c2vbuccni {
  cx: 12px;
  cy: 10.5px;
  r: 3.5px;
}

.ha2z4qbtg {
  d: path("M2.75 3h18.5v15H2.75z");
}

.hdj66lbws {
  d: path("M6 21.25h12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
