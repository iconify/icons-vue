<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q2li-tkqb"/><path class="lwi3fjb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-weight" /></template>
<style>
.lwi3fjb_g {
  d: path("M7.5 10a4.5 4.5 0 0 1 9 0Zm4.5 0l2.25-2.5M9.5 17.25a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0Zm-.75-3h.01M12 13h.01m3.24 1.25h.01");
}

.q2li-tkqb {
  d: path("M4.5 2.5h15a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
