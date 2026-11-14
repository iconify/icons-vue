<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nscw-c0yc"/><path class="g-t4v1n-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-arms-up" /></template>
<style>
.g-t4v1n-a {
  d: path("m5.5 3.5l3 5.5h7l3-5.5");
}

.nscw-c0yc {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 4v6m-3 6l3-6l3 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
