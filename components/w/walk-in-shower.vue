<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tn_w17bje"/><path class="bcazfxb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:walk-in-shower" /></template>
<style>
.bcazfxb5p {
  d: path("M7.5 8a4.5 3 0 0 1 9 0ZM9 11.5v2m3-2v2m3-2v2m-4.5 3v2m3-2v2");
}

.tn_w17bje {
  d: path("M4 21.5v-17a2 2 0 0 1 2-2h6V5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
