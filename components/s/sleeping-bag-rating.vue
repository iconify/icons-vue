<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e_xvppb6d"/><path class="d58yaepsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sleeping-bag-rating" /></template>
<style>
.d58yaepsd {
  d: path("M6.25 7.75a2.75 2 0 1 0 5.5 0a2.75 2 0 1 0-5.5 0Zm12.5 8v6m-2.5-4.5l5 3m-5 0l5-3");
}

.e_xvppb6d {
  d: path("M12.932 20.213q-.055.145-.132.279t-.173.256t-.211.226q-.115.105-.244.191t-.27.152q-.141.065-.29.107q-.149.043-.303.062T11 21.5H7q-.169.005-.337-.018q-.167-.023-.329-.074q-.161-.051-.311-.128q-.151-.077-.286-.179q-.136-.102-.252-.224t-.21-.264q-.095-.14-.164-.295T5 20L3.5 8.5c0-3.5 1.5-6 5.5-6s5.5 2.5 5.5 6l-1.05 8.048");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
