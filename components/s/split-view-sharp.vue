<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ejk2p2aad"/><path class="uj835yadn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:split-view-sharp" /></template>
<style>
.ejk2p2aad {
  d: path("M2.75 3.75h18.5v16.5H2.75zM12 4.5v15");
}

.uj835yadn {
  d: path("m9 10l-2 2l2 2m6-4l2 2l-2 2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
