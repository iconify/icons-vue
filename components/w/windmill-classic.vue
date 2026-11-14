<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a6imjacze"/><path class="dpwl4tbld"/><path class="v-e_nsbpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:windmill-classic" /></template>
<style>
.a6imjacze {
  d: path("m16.243 2.386l2.121 2.121l-4.243 4.243l4.243 4.243l-2.121 2.121L12 10.871l-4.243 4.243l-2.121-2.121L9.879 8.75L5.636 4.507l2.121-2.121L12 6.629Z");
}

.dpwl4tbld {
  d: path("m11 12l-4 9.5h10L13 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-e_nsbpd {
  d: path("M10.75 21.5v-2.75a1.25 1.25 0 0 1 2.5 0v2.75");
}

</style>
