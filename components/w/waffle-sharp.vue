<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="y7c3_el2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waffle-sharp" /></template>
<style>
.nciaxcb6w {
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7c3_el2g {
  d: path("M6.25 6.25h4v4h-4zm7.5 0h4v4h-4zm-7.5 7.5h4v4h-4zm7.5 0h4v4h-4z");
}

</style>
