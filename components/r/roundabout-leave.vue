<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xa8rgebsh"/><path class="uox6z4w9a"/><path class="lz5opjb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roundabout-leave" /></template>
<style>
.lz5opjb0p {
  d: path("M18.75 8.25L21.5 11l-2.75 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uox6z4w9a {
  d: path("M10 20.5V17a6 6 0 0 0 6-6h5.5");
}

.xa8rgebsh {
  d: path("M16 11a6 6 0 1 1-6-6");
}

</style>
