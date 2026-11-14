<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v-wqvcbvd"/><path class="drq3_s0pm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rowan-berries" /></template>
<style>
.drq3_s0pm {
  fill: currentColor;
  d: path("M2.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM9 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8.5-2.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-wqvcbvd {
  d: path("M11 9c1-4 4.5-6 10-6c-.5 4.5-5 6.5-10 6Zm0 0l-6.5 5.5M11 9v8m0-8l8.5 5.5");
}

</style>
