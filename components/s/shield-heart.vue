<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hnvnn0bgl"/><path class="nnjygtm-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shield-heart" /></template>
<style>
.hnvnn0bgl {
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6Z");
}

.nnjygtm-b {
  d: path("M12 15.5S8 13 8 10.25c0-1.35 1-2.5 2.25-2.5c.75 0 1.35.35 1.75 1c.4-.65 1-1 1.75-1C15 7.75 16 8.9 16 10.25c0 2.75-4 5.25-4 5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
