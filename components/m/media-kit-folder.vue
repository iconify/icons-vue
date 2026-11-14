<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y8gikqbpr"/><path class="ivin4_1hp"/><path class="xtir6tbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:media-kit-folder" /></template>
<style>
.ivin4_1hp {
  d: path("M10.5 9.25h3v3.5h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtir6tbak {
  d: path("M7.5 11a4.5 4.5 0 0 0 9 0M12 15.5v1.75");
}

.y8gikqbpr {
  d: path("M2.5 6A1.5 1.5 0 0 1 4 4.5h5l2 2h9A1.5 1.5 0 0 1 21.5 8v10.5A1.5 1.5 0 0 1 20 20H4a1.5 1.5 0 0 1-1.5-1.5Z");
}

</style>
