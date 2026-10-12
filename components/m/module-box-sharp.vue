<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k46rdzb2e"/><path class="j5d-ujy9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:module-box-sharp" /></template>
<style>
.j5d-ujy9l {
  d: path("M7.25 7L12 9.75L16.75 7M12 9.75V20m-9.25-8h1.5m15.5 0h1.5");
}

.k46rdzb2e {
  d: path("m13.08 3.89l3.34 1.97l1.08.64v11l-1.08.64l-3.34 1.97l-1.08.64l-1.08-.64l-3.34-1.97l-1.08-.64v-11l1.08-.64l3.34-1.97L12 3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
