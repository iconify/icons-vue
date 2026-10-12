<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kp86mcd4u"/><path class="p9bhuub8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:video-chapters-sharp" /></template>
<style>
.kp86mcd4u {
  d: path("M2.75 3.75h18.5v11.5H2.75z");
}

.p9bhuub8s {
  d: path("m10.86 7.59l2.78 1.57l.61.34l-.61.34l-2.78 1.57l-.61.34v-4.5zM2.75 19.75h4.5m3 0h4m3 0h4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
