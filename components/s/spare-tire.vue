<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qqb294baw"/><path class="rvrq3-biv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spare-tire" /></template>
<style>
.qqb294baw {
  d: path("M3.5 11.5a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0ZM4 20h16");
}

.rvrq3-biv {
  d: path("M7.5 11.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM12 10h.01m-1.26 2.5h.01m2.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
