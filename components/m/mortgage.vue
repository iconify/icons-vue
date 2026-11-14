<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ankajwbyj"/><path class="or8ccep1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage" /></template>
<style>
.ankajwbyj {
  d: path("M11.931 21H3V10.5L12 3l9 7.5v2.569");
}

.or8ccep1z {
  d: path("M7 21v-3.5a2 2 0 0 1 4 0V21m3.75-3.75l3.5-2.75l3.5 2.75m-7 0h7m-5.5 0v4.25m4-4.25v4.25m-5.5 0h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
