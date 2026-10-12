<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmolhex5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:maracas-sharp" /></template>
<style>
.nmolhex5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.6 3.81a3 3.75-10 1 0 1.3 7.38a3 3.75-10 1 0-1.3-7.38Zm10.8 0a3 3.75 10 1 1-1.3 7.38a3 3.75 10 1 1 1.3-7.38Zm-9.5 7.38l1.56 8.86m6.64-8.86l-1.56 8.86");
}

</style>
