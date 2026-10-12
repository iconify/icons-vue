<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r0g-oktfp"/><path class="ocvhuaccq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sticky-keys-sharp" /></template>
<style>
.ocvhuaccq {
  d: path("M6.75 14.5v-4.25M5 12l1.75-1.75L8.5 12m7.25 0h3M5 20.75h14");
}

.r0g-oktfp {
  d: path("M2.75 6.75h8v10.5h-8zm10.5 0h8v10.5h-8z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
