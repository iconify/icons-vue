<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ty8g312dz"/><path class="heaf5tr2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:team-signup" /></template>
<style>
.heaf5tr2r {
  d: path("M6.5 6h8v3h-8Zm0 7h8m.25 5l2 2L21 15.75");
}

.ty8g312dz {
  d: path("M14.3 21.5H3.5v-19h14v12.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
