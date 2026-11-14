<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jubfapb0u"/><path class="vjm7jcbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stethoscope-heart" /></template>
<style>
.jubfapb0u {
  d: path("M14.25 20s-6-3.5-6-7.5c0-1.75 1.5-3 3.25-3c1 0 2.25.75 2.75 1.5c.5-.75 1.75-1.5 2.75-1.5c1.75 0 3.25 1.25 3.25 3c0 4-6 7.5-6 7.5ZM3 2.5v3C3 7.5 4.5 9 6.5 9S10 7.5 10 5.5v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjm7jcbak {
  d: path("M6.5 9v3.5c0 1.5 1 2.25 2.5 2.25h3m.25-.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
