<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d5sffgbre"/><path class="u6wshxghz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:raincoat-sharp" /></template>
<style>
.d5sffgbre {
  d: path("m8.27 5.87l.46-.99l.52-1.13l1.17-.43l.41-.14L12 2.75l1.17.43l.41.14l1.17.43l.52 1.13l.46.99l.52 1.13l1.15.49l1.2.52l1.15.49l.16 1.24l1.18 9.27l.16 1.24l-1.2.34l-1.1.32l-1.2.34H6.25l-1.2-.34l-1.1-.32l-1.2-.34l.16-1.24l1.18-9.27l.16-1.24l1.15-.49l1.2-.52L7.75 7z");
}

.u6wshxghz {
  d: path("M10.5 8V5.75h3V8M12 10v11.25M6.25 12.5v8.75m11.5-8.75v8.75M4 2.75L2.75 4.625v.525a1.25 1.25 0 0 0 2.5 0v-.525zm16 0l-1.25 1.875v.525a1.25 1.25 0 0 0 2.5 0v-.525z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
