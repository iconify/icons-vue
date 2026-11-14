<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jsyeb5b-u"/><path class="esfyz7x2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:space-book" /></template>
<style>
.esfyz7x2n {
  d: path("M6.5 6a5.5 1.5 0 1 0 11 0a5.5 1.5 0 1 0-11 0Z");
}

.jsyeb5b-u {
  d: path("M12 21c-2.5-1.5-6-2-9.5-1.5v-8c3.5-.5 7 0 9.5 1.5c2.5-1.5 6-2 9.5-1.5v8c-3.5-.5-7 0-9.5 1.5Zm0-8v8M9.25 6a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
