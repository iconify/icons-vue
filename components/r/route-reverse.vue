<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jpombbjnt"/><path class="u7bhvi1sx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-reverse" /></template>
<style>
.jpombbjnt {
  d: path("M3 18.5h12a3.5 3.5 0 0 0 0-7H9a3.5 3.5 0 0 1 0-7h12");
}

.u7bhvi1sx {
  d: path("M5.5 16L3 18.5L5.5 21m13-19L21 4.5L18.5 7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
