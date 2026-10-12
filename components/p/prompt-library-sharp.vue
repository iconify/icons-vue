<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v5epcnbiu"/><path class="umdzaccwd"/><path class="h6h5yxboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prompt-library-sharp" /></template>
<style>
.h6h5yxboh {
  d: path("m6.25 12.5l2.25 2.25L6.25 17m4.5 0h3");
}

.umdzaccwd {
  d: path("M2.75 8.75h15v12.5h-15z");
}

.v5epcnbiu {
  d: path("M6.25 5.25h15v12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
