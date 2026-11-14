<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o7c1arvsc"/><path class="prjir8y6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-guarantor" /></template>
<style>
.o7c1arvsc {
  d: path("M12.06 20.5H4v-10l8-7l8 7v.64");
}

.prjir8y6d {
  d: path("M16 7V4h2v4.75M16.5 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1.75 6.5c0-1.25 1.5-2.25 3.25-2.25s3.25 1 3.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
