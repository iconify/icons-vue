<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vni3pi4oq"/><path class="of95kqb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:okr" /></template>
<style>
.of95kqb6k {
  d: path("M5.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10-5h6m-6 5h4m-4 5H18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vni3pi4oq {
  d: path("M2.5 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
