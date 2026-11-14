<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="anibpm6gc"/><path class="gvs6g-b0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marker-square" /></template>
<style>
.anibpm6gc {
  d: path("M4 3.5h16v13h-5.25L12 21l-2.75-4.5H4Z");
}

.gvs6g-b0k {
  d: path("M9.5 7.5h5v5h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
