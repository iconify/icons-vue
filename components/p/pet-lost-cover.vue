<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ydwudw6zd"/><path class="b5d1zcbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-lost-cover" /></template>
<style>
.b5d1zcbse {
  d: path("M10.5 14.5c-1.25 0-2-.6-2-1.5c0-.75 1-1.25 2-1.25s2 .5 2 1.25c0 .9-.75 1.5-2 1.5ZM8 10.25h.01M9.5 8.5h.01m1.99 0h.01M13 10.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydwudw6zd {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm12 5l5 5");
}

</style>
