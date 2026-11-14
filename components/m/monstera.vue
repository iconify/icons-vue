<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izgkwbc9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monstera" /></template>
<style>
.izgkwbc9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3a8.5 8.5 0 0 1 7 3.75L15 9.5l5.25-.25a8.5 8.5 0 0 1 0 3.75l-5.25.75l4 2.5A8.5 8.5 0 0 1 12 20a8.5 8.5 0 0 1-7-3.75l4-2.5L3.75 13a8.5 8.5 0 0 1 0-3.75L9 9.5L5 6.75A8.5 8.5 0 0 1 12 3Zm0 3.5v15.25");
}

</style>
