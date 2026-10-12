<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><circle class="o5__hii-l"/><path class="r75vddc6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tambourine-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.o5__hii-l {
  cx: 12px;
  cy: 12px;
  r: 4.5px;
}

.r75vddc6t {
  d: path("m18.5 14.48l-1.1 1.91m-4.3 2.49h-2.2m-4.3-2.49l-1.1-1.91m0-4.96l1.1-1.91m4.3-2.49h2.2m4.3 2.49l1.1 1.91");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
