<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="agaj3h_lu"/><path class="qd4iqlb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stomach-sharp" /></template>
<style>
.agaj3h_lu {
  d: path("M14.5 2.75v4.583l1.25.417c2.5.75 4.5 2.75 4.5 6c0 4.25-3.75 7.5-8.5 7.5c-3 0-5.5-1.25-7-3.25l-1.364-1.818l1.864-.932l1.5-.75L8 15.75l1.607 1.607L11.75 17c2-.35 3-2 2.25-3.75l-.472-1.181l-2.278-.569l-1.75-.42V2.75Z");
}

.qd4iqlb_k {
  d: path("m15 10.75l2.633 1.317l-.383 2.683");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
