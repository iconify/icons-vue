<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="de4txlbkz"/><path class="zip6x2byd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:playhouse" /></template>
<style>
.de4txlbkz {
  d: path("M13.16 20.5H4v-10l8-7l8 7v3.24");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zip6x2byd {
  d: path("M16 7V4h2v4.75m-2 5.75l5.5 3.5l-5.5 3.5Z");
}

</style>
