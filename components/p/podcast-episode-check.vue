<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rdjbrvbvd"/><path class="oslqirbld"/><path class="pcyew975a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-episode-check" /></template>
<style>
.oslqirbld {
  d: path("M13.5 2.5v3h3M9 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.pcyew975a {
  d: path("M7.348 15.652a3.75 3.75 0 1 1 5.304 0M10 14v4.75m4.75-.75l2 2L21 15.75");
}

.rdjbrvbvd {
  d: path("M14.343 21.5H3.5v-19h10l3 3v10.357");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
