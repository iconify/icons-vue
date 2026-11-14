<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="th616nbyz"/><path class="o51o1jb0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newsletter-issue-check" /></template>
<style>
.o51o1jb0r {
  d: path("m7 6l4 3l4-3m-8 6.5h8m-8 4h4m3.75 1.5l2 2L21 15.75");
}

.th616nbyz {
  d: path("M14.3 21.5H3.5v-19h15v11.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
