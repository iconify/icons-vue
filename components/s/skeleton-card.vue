<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oda4a2bll"/><path class="m3bq06brf"/><path class="u0cfjfaql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skeleton-card" /></template>
<style>
.m3bq06brf {
  fill: currentColor;
  d: path("M6 6.5h4v4H6Z");
}

.oda4a2bll {
  d: path("M3 3.5h18v17H3Z");
}

.u0cfjfaql {
  d: path("M6 13.5h12m-12 4h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
