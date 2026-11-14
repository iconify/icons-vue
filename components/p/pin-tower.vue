<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dr7wq0bqh"/><path class="ueejwcmum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-tower" /></template>
<style>
.dr7wq0bqh {
  d: path("M7 21.5v-13l5-6l5 6v13m-12.5 0h15");
}

.ueejwcmum {
  d: path("M10.5 21.5V18a1.5 1.5 0 0 1 3 0v3.5m-1.5-10v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
