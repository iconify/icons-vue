<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="cw_i6m1pd"/><path class="nfoe96jjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:running-sharp" /></template>
<style>
.cw_i6m1pd {
  cx: 14.75px;
  cy: 5px;
  r: 2px;
}

.nfoe96jjk {
  d: path("m7 10.25l3.25-2.5h3.5l2 3l2.75 1m-4.75-4L11 13.25L14.25 16l-1 4.75M11 13.25l-2 3.5l-3.75.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
