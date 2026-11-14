<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gz20jt62h"/><path class="zcssy_b5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:targeted-therapy" /></template>
<style>
.gz20jt62h {
  d: path("M3.5 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zcssy_b5v {
  d: path("M12 7.5C13.25 7 14 8 14 9c1-.5 2 .5 1.75 1.5C17 11 17 12.75 16 13.25c.25 1.25-.75 2.25-2 2c-.5 1.25-2 1.75-2.75.75c-1 .5-2.5 0-2.25-1.25c-1.5-.25-2-1.75-1-2.5c-.75-1 0-2.5 1-2.5c0-1.25 1.5-2 2.5-1.5c0-.5 0-.75.5-.75Zm0-5v3m0 13v3M2.5 12h3m13 0h3");
}

</style>
