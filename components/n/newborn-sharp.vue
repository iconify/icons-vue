<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rr-nm9b_q"/><circle class="argn9bbqd"/><path class="ktnabfbml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:newborn-sharp" /></template>
<style>
.argn9bbqd {
  cx: 12px;
  cy: 8.25px;
  r: 2.75px;
}

.ktnabfbml {
  d: path("m6.75 13.5l10.5 3.5");
}

.rr-nm9b_q {
  d: path("M6.75 3h10.5v18.25H6.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
