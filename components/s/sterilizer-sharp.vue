<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="paf2sow1n"/><path class="r5h59gbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sterilizer-sharp" /></template>
<style>
.paf2sow1n {
  d: path("M4.5 2.75h15V19.5h-15z");
}

.r5h59gbut {
  d: path("M7.5 5h9v2.25h-9zM10 9.5v.75m4-.75v.75m-9.5 2h15m-11.25 4h7.5M7.5 19.5v1.75m9-1.75v1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
