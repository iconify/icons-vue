<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jj9sdy8si"/><path class="n75-c-bbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-age-limit" /></template>
<style>
.jj9sdy8si {
  d: path("M12.169 13.967C10.817 13.625 9.539 12.692 8.5 12l-4.5.25c-1 0-1.5-.75-1.5-1.75S3 9 3.5 8.75l4-1.25c.5-2.5 2.5-4 5-4c3 0 5 2.25 5 5.5c0 1.036-.258 1.943-.702 2.704");
}

.n75-c-bbk {
  d: path("M13 3.75c2.75 1 3.75 4.75 2.5 7.75C14 11.5 13 9 13 3.75ZM9.5 8h.01M15 15.5h6v5.75h-6Zm0 2.25h6m-4.25-3.25V16m2.5-1.5V16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
