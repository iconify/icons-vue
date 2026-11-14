<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bbty41fhy"/><path class="czugb3f-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:package-size" /></template>
<style>
.bbty41fhy {
  d: path("m12 2.5l8 4v7l-8 4l-8-4v-7Z");
}

.czugb3f-q {
  d: path("m4 6.5l8 4l8-4m-8 4v7m-8 3h16M4 19v3m16-3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
