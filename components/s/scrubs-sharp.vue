<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="psc5_0bce"/><path class="gkgyf6rls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scrubs-sharp" /></template>
<style>
.gkgyf6rls {
  d: path("M12 11h3v3.25h-3z");
}

.psc5_0bce {
  d: path("m9.14 4.02l2.22 2.71l.64.77l.64-.77l2.22-2.71l.64-.77l.93.37l3.14 1.26l.93.37l.12.99l.51 4.02l.12.99l-.97.22l-1.31.31L18 12v9.25H6V12l-.97-.22l-1.31-.31l-.97-.22l.12-.99l.51-4.02l.12-.99l.93-.37l3.14-1.26l.93-.37z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
