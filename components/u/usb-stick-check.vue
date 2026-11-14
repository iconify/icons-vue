<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h9jlpgcwn"/><path class="u57o3obdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:usb-stick-check" /></template>
<style>
.h9jlpgcwn {
  d: path("M7 9h10v12.5H7Zm1.5-6.5h7V9h-7Zm2.25 3.25h2.5");
}

.u57o3obdo {
  d: path("m9.75 15.5l1.75 1.75l3-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
