<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2k0h6ryu"/><path class="pfetj78he"/><path class="zy5ie8b4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-vineyard" /></template>
<style>
.p2k0h6ryu {
  d: path("M4.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.pfetj78he {
  d: path("M7 13.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zy5ie8b4l {
  d: path("M9.5 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM12 7c0-2 1-3.25 3-3.5");
}

</style>
