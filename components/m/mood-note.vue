<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t49li2qab"/><path class="sern725pt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-note" /></template>
<style>
.sern725pt {
  d: path("M15.031 10.25a3.5 3.5 0 0 1-6.062 0M7 15h9.5M7 18h6");
}

.t49li2qab {
  d: path("M5.5 3.5h13a2 2 0 0 1 2 2V15L15 20.5H5.5a2 2 0 0 1-2-2v-13a2 2 0 0 1 2-2Zm4 3.5h.01m4.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
