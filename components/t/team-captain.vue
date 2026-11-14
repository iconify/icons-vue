<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fvjgovbrj"/><path class="zvthjybbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:team-captain" /></template>
<style>
.fvjgovbrj {
  d: path("M8.75 5.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM3.5 21.5v-2c0-4.5 3.75-7.25 8.5-7.25s8.5 2.75 8.5 7.25v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zvthjybbm {
  d: path("m12 15l.735 1.989l2.118.084l-1.664 1.313l.574 2.041L12 19.25l-1.763 1.177l.574-2.041l-1.664-1.313l2.118-.084Zm-8.25 2.5h2.5");
}

</style>
