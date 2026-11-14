<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e51izacuh"/><path class="xx315_b4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nursery-lamp" /></template>
<style>
.e51izacuh {
  d: path("M17 4.5A7.5 7.5 0 1 0 18.5 15A6 6 0 0 1 17 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xx315_b4g {
  d: path("M8.5 18h8v3h-8Z");
}

</style>
