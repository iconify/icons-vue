<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1rkz-enw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stair-lift-sharp" /></template>
<style>
.g1rkz-enw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h5v-4.5h5v-4.5h5v-4.5h3.5M3 17L19 5M9.35 3.75h1.9v5h3v2h-5.5v-7z");
}

</style>
