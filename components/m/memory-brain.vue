<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ss7sk8bog"/><path class="ecziz5b4d"/><path class="nfdct5bvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:memory-brain" /></template>
<style>
.ecziz5b4d {
  d: path("M7.5 10.5c1-2.25 3.5-2.25 4 0M14 7.25c1.5.5 2.25 1.75 1.5 3.25m-.75 7.5a3.25 3.25 0 1 1 1 2.25");
}

.nfdct5bvl {
  d: path("M13.5 16.75L14.75 18L16 16.75");
}

.ss7sk8bog {
  d: path("M12.273 14H6.5c-2.5 0-4-1.75-3.5-3.5c-1-2.25.5-4.75 3-5.25c.75-2 3.75-3 6-2c2-1 5.25-.5 6.25 1.75c2.25.75 3.25 3.5 1.75 5.25c.156.701.069 1.329-.2 1.862");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
