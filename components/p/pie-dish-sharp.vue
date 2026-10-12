<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kb8jnrbyb"/><path class="lw9hoebsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pie-dish-sharp" /></template>
<style>
.kb8jnrbyb {
  d: path("M3.25 14C4.5 11 7.75 9 12 9s7.5 2 8.75 5a1.75 1 0 0 1-3.5 0a1.75 1 0 0 1-3.5 0a1.75 1 0 0 1-3.5 0a1.75 1 0 0 1-3.5 0a1.75 1 0 0 1-3.5 0ZM9 12.25l1.5-.75m4.5.75l-1.5-.75");
}

.lw9hoebsq {
  d: path("M3.25 14a1.75 1 0 0 0 3.5 0a1.75 1 0 0 0 3.5 0a1.75 1 0 0 0 3.5 0a1.75 1 0 0 0 3.5 0a1.75 1 0 0 0 3.5 0h.5l-1.4 3.9l-.466 1.356l-1.434-.006H6.05l-1.434.006L4.15 17.9L2.75 14Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
