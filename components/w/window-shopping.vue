<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z9zma3bug"/><path class="e_qep-b4r"/><path class="aw2rqvbsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:window-shopping" /></template>
<style>
.aw2rqvbsi {
  d: path("M10.5 16.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.e_qep-b4r {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 16.25c2-2.75 9-2.75 11 0c-2 2.75-9 2.75-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9zma3bug {
  d: path("m3 9l1.5-5h15L21 9M4 11h16v10.5H4Z");
}

</style>
