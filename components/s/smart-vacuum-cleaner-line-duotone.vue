<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="smmug3biq"/><path class="htapwebmh"/><path class="gshkn9qqt"/><path class="srug0hb7t"/><path class="wyvi3vbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-vacuum-cleaner-line-duotone" /></template>
<style>
.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.htapwebmh {
  d: path("M7.35462 20.8579C6.84413 21.2601 6.19984 21.5001 5.49951 21.5001C3.84266 21.5001 2.49951 20.1569 2.49951 18.5001C2.49951 17.7996 2.73954 17.1553 3.14183 16.6448");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.smmug3biq {
  d: path("M16.6451 20.8579C17.1555 21.26 17.7998 21.4999 18.5 21.4999C20.1569 21.4999 21.5 20.1568 21.5 18.4999C21.5 17.7997 21.2601 17.1555 20.858 16.645");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.srug0hb7t {
  d: path("M15 9C15 10.6569 13.6569 12 12 12C10.3431 12 9 10.6569 9 9C9 7.34315 10.3431 6 12 6C13.6569 6 15 7.34315 15 9Z");
}

.wyvi3vbxo {
  d: path("M12 18V16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
