<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xm2qfxbzr"/><path class="infvveb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:screening" /></template>
<style>
.infvveb4y {
  d: path("m16.25 18l1.25 1.25l2.25-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xm2qfxbzr {
  d: path("M11.636 19.5h-.386c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l1.468 1.835m-1.968 1.416V13.5L12 12l.5 2l.067.379M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 13.75a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

</style>
