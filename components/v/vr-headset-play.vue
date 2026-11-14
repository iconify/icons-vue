<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cau7gub2n"/><path class="sdye8e7wg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vr-headset-play" /></template>
<style>
.cau7gub2n {
  d: path("M7 6h10a2.5 2.5 0 0 1 2.5 2.5v7A2.5 2.5 0 0 1 17 18h-2a3 2 0 0 0-6 0H7a2.5 2.5 0 0 1-2.5-2.5v-7A2.5 2.5 0 0 1 7 6Zm-4.5 5.5h2m15 0h2");
}

.sdye8e7wg {
  d: path("m10 8.5l4.5 2.5l-4.5 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
