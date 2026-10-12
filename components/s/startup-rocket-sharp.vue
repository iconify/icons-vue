<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vjdhy5bsn"/><circle class="qdenhg52p"/><path class="i2w489b3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:startup-rocket-sharp" /></template>
<style>
.i2w489b3w {
  d: path("M9.5 8.5H6.25L4 10.75h3.25m8.25 3.75v3.25L13.25 20v-3.25m-3.5-1l-4.5 4.5m1.25-6l-2 2m6.75 2.25l-2 2");
}

.qdenhg52p {
  cx: 15.25px;
  cy: 8.75px;
  r: 1.5px;
}

.vjdhy5bsn {
  d: path("M20.75 3.25c-3.5-.25-6.75 1.25-9 3.5l-3.5 3.5l5.5 5.5l3.5-3.5c2.25-2.25 3.75-5.5 3.5-9Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
