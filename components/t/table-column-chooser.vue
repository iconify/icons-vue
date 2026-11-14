<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xxh2v5byu"/><path class="u2fvy8bxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:table-column-chooser" /></template>
<style>
.u2fvy8bxx {
  d: path("m4.5 4.75l1 1l1.25-2m10.5 1l1 1l1.25-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxh2v5byu {
  d: path("M2.5 9.5h19v12h-19Zm6.25 0v12m6.5-12v12m-12.75-8h19m-18-11h4.25v4.25H3.5Zm6.25 0h4.5v4.25h-4.5Zm6.5 0h4.25v4.25h-4.25Z");
}

</style>
