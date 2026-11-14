<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ncal7lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prompt-variables" /></template>
<style>
.n_ncal7lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5H8A2.5 2.5 0 0 0 5.5 6v3.75A2.25 2.25 0 0 1 3.25 12a2.25 2.25 0 0 1 2.25 2.25V18A2.5 2.5 0 0 0 8 20.5h.5m7-17h.5A2.5 2.5 0 0 1 18.5 6v3.75A2.25 2.25 0 0 0 20.75 12a2.25 2.25 0 0 0-2.25 2.25V18a2.5 2.5 0 0 1-2.5 2.5h-.5M10 12h4");
}

</style>
