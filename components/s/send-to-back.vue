<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jimxtbgkt"/><path class="p85i7rbet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:send-to-back" /></template>
<style>
.jimxtbgkt {
  d: path("M2.5 5.5H11V14H2.5Z");
}

.p85i7rbet {
  d: path("M11 10h2a2 2 0 0 1 2 2v4.5a2 2 0 0 1-2 2H8.5a2 2 0 0 1-2-2V14m13-8.5v13m-1.75-1.75l1.75 1.75l1.75-1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
