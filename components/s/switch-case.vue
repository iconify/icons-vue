<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b3i39ombu"/><path class="etatracfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:switch-case" /></template>
<style>
.b3i39ombu {
  d: path("M2.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0H20M9 12c3 0 3-7 6-7h5M9 12c3 0 3 7 6 7h5");
}

.etatracfm {
  d: path("m18 3l2 2l-2 2m0 3l2 2l-2 2m0 3l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
