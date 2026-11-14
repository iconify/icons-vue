<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gn2obmb1s"/><path class="afuxdilot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speed-bump-sign" /></template>
<style>
.afuxdilot {
  d: path("M7.5 17H9a3 3 0 0 1 6 0h1.5");
}

.gn2obmb1s {
  d: path("M12 2.75L21.75 20H2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
