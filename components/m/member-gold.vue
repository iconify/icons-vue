<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvkw6zboz"/><path class="nkv77ywgc"/><path class="s8xhoh91p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:member-gold" /></template>
<style>
.nkv77ywgc {
  d: path("M5.75 15a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0Z");
}

.pvkw6zboz {
  d: path("M6.5 2.5H10L12 6l2-3.5h3.5l-3 6.5h-5Z");
}

.s8xhoh91p {
  d: path("M8.75 17.5V13l1.75 1.5l1.5-2.25l1.5 2.25l1.75-1.5v4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
