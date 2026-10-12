<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rqid0z5ms"/><path class="o8o85fbpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slippers-spa-sharp" /></template>
<style>
.o8o85fbpj {
  d: path("M3.06 10.15q3.39-3.12 7.36-.77l.08 2.25l-3.79-2.11l-3.27 2.85Zm10.52-.77q3.97-2.35 7.36.77l-.38 2.22l-3.27-2.85l-3.79 2.11Z");
}

.rqid0z5ms {
  d: path("M2.85 8.66a3.75 4-6 0 1 7.46-.78c.37 3.48-.42 5.57-.05 9.06a2.75 3-6 0 1-5.47.57c-.37-3.48-1.57-5.37-1.94-8.85Zm10.84-.78a3.75 4 6 0 1 7.46.78c-.37 3.48-1.57 5.37-1.94 8.85a2.75 3 6 0 1-5.47-.57c.37-3.49-.42-5.58-.05-9.06Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
