<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tnyzzg7cl"/><path class="w8h5xfbfv"/><path class="iwj-9gb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-tag-property" /></template>
<style>
.iwj-9gb7f {
  d: path("M11 8C9 5.5 6 4.5 3 6m5.5 9h7m-7 3h4");
}

.tnyzzg7cl {
  d: path("m12 2.5l7.5 7.5v11.5h-15V10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8h5xfbfv {
  d: path("M10.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
