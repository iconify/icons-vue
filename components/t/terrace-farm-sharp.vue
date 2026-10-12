<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w3m1r4hic"/><path class="gvu5eetdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:terrace-farm-sharp" /></template>
<style>
.gvu5eetdc {
  d: path("M11 21.25V17.5h3.5V14H18v-3.5h3.25");
}

.w3m1r4hic {
  d: path("M3.53 20.72L20.72 3.53l.53-.53v18.25H3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
