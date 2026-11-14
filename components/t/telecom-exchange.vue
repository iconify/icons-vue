<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr6cu2yja"/><path class="eg-sbva4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:telecom-exchange" /></template>
<style>
.eg-sbva4i {
  d: path("M9 19.75v-4.5h6v4.5");
}

.fr6cu2yja {
  d: path("M2.5 4.25h19M4 4.25v15.5h16V4.25M7.5 7.75v4m3-4v4m3-4v4m3-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
