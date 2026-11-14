<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="phzz9fbox"/><path class="v4hkxp3ww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swimmer-breaststroke" /></template>
<style>
.phzz9fbox {
  d: path("M8.75 7.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4hkxp3ww {
  d: path("M3 10c2.5 3.5 6 3.75 9 3.75s6.5-.25 9-3.75M2.5 18.5q2.25-1.75 4.75 0q2.25 1.75 4.75 0q2.25-1.75 4.75 0q2.25 1.75 4.75 0");
}

</style>
