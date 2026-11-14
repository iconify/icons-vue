<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6nv6e4rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-landslide" /></template>
<style>
.p6nv6e4rz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3L15 21h6.5M8.906 3.456l.519-.311a1.5 1.5 0 0 1 1.901.299l.229.262a1.5 1.5 0 0 1 .183 1.716l-.259.466a1.5 1.5 0 0 1-1.46.764l-.415-.042a1.5 1.5 0 0 1-1.322-1.198l-.075-.375a1.5 1.5 0 0 1 .699-1.581m5.1 5.041l.457-.229a1.5 1.5 0 0 1 1.8.354l.292.334a1.5 1.5 0 0 1 .183 1.716l-.259.466a1.5 1.5 0 0 1-1.46.764l-.395-.04a1.5 1.5 0 0 1-1.326-1.224l-.097-.531a1.5 1.5 0 0 1 .805-1.61m3.72 5.867l.359-.313a1.5 1.5 0 0 1 1.888-.071l.271.203a1.5 1.5 0 0 1 .571 1.494l-.095.475a1.5 1.5 0 0 1-1.335 1.199l-.415.038a1.5 1.5 0 0 1-1.572-1.063l-.121-.402a1.5 1.5 0 0 1 .449-1.56");
}

</style>
