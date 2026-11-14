<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aebzwpecv"/><path class="wk1h86p2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:merge-game" /></template>
<style>
.aebzwpecv {
  d: path("m16 10l4.75 2.75v5.5L16 21l-4.75-2.75v-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wk1h86p2u {
  d: path("M11.25 12.75L16 15.5l4.75-2.75M16 15.5V21m0-18.5v4.75m-2-2l2 2l2-2M2.5 15.5h6m-2-2l2 2l-2 2");
}

</style>
