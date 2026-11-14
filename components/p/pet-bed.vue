<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j7mg2bt4p"/><path class="ejg2llban"/><path class="c49-ofb-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-bed" /></template>
<style>
.c49-ofb-z {
  d: path("M7 10.25a5 2.5 0 1 0 10 0a5 2.5 0 1 0-10 0Z");
}

.ejg2llban {
  d: path("M2.5 11v3a9.5 6 0 0 0 19 0v-3");
}

.j7mg2bt4p {
  d: path("M2.5 11a9.5 6 0 1 0 19 0a9.5 6 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
