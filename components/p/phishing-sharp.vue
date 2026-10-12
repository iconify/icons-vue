<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qw4x7ebul"/><path class="du2tnkioy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phishing-sharp" /></template>
<style>
.du2tnkioy {
  d: path("M2.75 13.25L8.25 17l5.5-3.75m6.5-10.5v14h-4v-5l1.5 1.5");
}

.qw4x7ebul {
  d: path("M2.75 11.25h11v9.5h-11z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
