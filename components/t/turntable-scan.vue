<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ug6ixtbef"/><path class="at_hver0q"/><path class="jshg1fb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:turntable-scan" /></template>
<style>
.at_hver0q {
  d: path("m11.5 5l3 1.75V10l-3 1.75l-3-1.75V6.75Z");
}

.jshg1fb2b {
  d: path("m8.5 6.75l3 1.75l3-1.75m-3 1.75v3.25M2.75 14a8.75 5 0 0 0 17.5 0m-1.5 1.5l1.5-1.5l1.5 1.5");
}

.ug6ixtbef {
  d: path("M6.5 14a5 2.25 0 1 0 10 0a5 2.25 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
