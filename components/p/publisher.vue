<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e893ag9rt"/><path class="rrmcyib6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:publisher" /></template>
<style>
.e893ag9rt {
  d: path("m3 9.5l9-6l9 6Zm1 0V21h16V9.5");
}

.rrmcyib6w {
  d: path("M12 13.5c-1.5-1-3.5-1.25-4.5-1V17c1-.25 3 0 4.5 1c1.5-1 3.5-1.25 4.5-1v-4.5c-1-.25-3 0-4.5 1Zm0 0V18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
