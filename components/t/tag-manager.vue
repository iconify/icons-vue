<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dhugf2w8a"/><path class="vqb1uwd9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tag-manager" /></template>
<style>
.dhugf2w8a {
  d: path("m2.5 12l5-6.5h14v13h-14Zm5 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vqb1uwd9p {
  d: path("m13 9l-2 3l2 3m3.5-6l2 3l-2 3");
}

</style>
