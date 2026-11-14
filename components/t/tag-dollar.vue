<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j6di7o7eh"/><path class="fv-2zm2tf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tag-dollar" /></template>
<style>
.fv-2zm2tf {
  d: path("M6 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11.5-1.75c0-.75-1-1.25-2.25-1.25S13 9.5 13 10.5s1 1.25 2.25 1.5s2.25.5 2.25 1.5s-1 1.5-2.25 1.5S13 14.5 13 13.75m2.25-6.25v9");
}

.j6di7o7eh {
  d: path("M2.5 12L7 4.5h14.5v15H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
