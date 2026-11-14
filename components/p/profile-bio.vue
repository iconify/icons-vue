<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hrvg60ypl"/><path class="j92dt3bnl"/><path class="b5oeb3bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:profile-bio" /></template>
<style>
.b5oeb3bzg {
  d: path("M8.5 10.75c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5M7 13.5h10M7 16.25h10M7 19h6.5");
}

.hrvg60ypl {
  d: path("M3.5 2h17v20h-17Z");
}

.j92dt3bnl {
  d: path("M10.25 6.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
