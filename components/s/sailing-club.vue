<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irdj4ac9c"/><path class="febfkcgtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sailing-club" /></template>
<style>
.febfkcgtn {
  d: path("M7.5 21.5v-4h3v4");
}

.irdj4ac9c {
  d: path("M3.5 13L9 7.5l5.5 5.5v8.5h-11Zm16-10.5v19m0-18.75l-5 2.5l5 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
