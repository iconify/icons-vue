<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f0qpqcb2g"/><path class="fqxl7jb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:project-linked" /></template>
<style>
.f0qpqcb2g {
  d: path("M2.5 11.5A1.5 1.5 0 0 1 4 10h2l1.5 1.5H9a1.5 1.5 0 0 1 1.5 1.5v6.5A1.5 1.5 0 0 1 9 21H4a1.5 1.5 0 0 1-1.5-1.5Zm11 0A1.5 1.5 0 0 1 15 10h2l1.5 1.5H20a1.5 1.5 0 0 1 1.5 1.5v6.5A1.5 1.5 0 0 1 20 21h-5a1.5 1.5 0 0 1-1.5-1.5ZM4 3.5h9.5V7H4Z");
}

.fqxl7jb6n {
  d: path("M10.75 3.5H20V7h-9.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
